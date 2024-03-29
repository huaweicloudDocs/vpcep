# 示例：配置跨VPC通信的终端节点<a name="vpcep_04_0000"></a>

## 场景描述<a name="zh-cn_topic_0178456506_zh-cn_topic_0173706811_zh-cn_topic_0171265864_section10781336"></a>

如果用户想要实现VPC间的资源通信，相比于通过公网IP的访问方式，VPC终端节点支持将VPC私密地连接到终端节点服务（云服务、用户私有服务），无需使用弹性公网IP，访问效率更高，组网更安全。

下面介绍如何通过调用[创建终端节点服务](创建终端节点服务.md)API和[创建终端节点](创建终端节点.md)API实现终端节点到终端节点服务的连接。API的调用方法请参见[如何调用API](如何调用API.md)。

>![](public_sys-resources/icon-note.gif) **说明：** 
>通过IAM服务获取到的Token有效期为24小时，需要使用同一个Token鉴权时，可以先将Token缓存，避免频繁调用。

## 前提条件<a name="section55791211124014"></a>

您需要规划VPC终端节点所在的区域信息，并根据区域确定调用API的Endpoint，详细信息请参见[终端节点（Endpoint）](终端节点（Endpoint）.md)。

## 创建终端节点服务<a name="section1447534515536"></a>

在本示例中，为云服务器创建了一个接口型的终端节点服务。

>![](public_sys-resources/icon-note.gif) **说明：** 
>创建终端节点服务前请先获取创建的必要信息，如服务后端资源的Port ID、所在的虚拟私有云（VPC）的VPC ID等，详情请参考[创建终端节点服务](创建终端节点服务.md)。

```
{ 
  "port_id": "4189d3c2-8882-4871-a3c2-d380272eed88",
  "vpc_id": "4189d3c2-8882-4871-a3c2-d380272eed80",
  "approval_enabled":false,
  "service_type":"interface",
  "server_type":"VM",
  "ports":
           [
             {
               "client_port":8080,
               "server_port":80,
               "protocol":"TCP"
             },
             { 
               "client_port":8081,
               "server_port":80,
               "protocol":"TCP"
             }
            ]
} 
```

-   port\_id：标识终端节点服务后端资源的ID。例如创建云服务器类型的终端节点服务，则对应云服务器IP地址对应的网卡ID。
-   vpc\_id：终端节点服务对应后端资源所在的VPC的ID。
-   approval\_enabled：终端节点连接终端节点服务是否需要审批，例如“false”，表示可以直接连接，不需要审批。
-   service\_type：终端节点服务类型。例如“interface”，表示接口类型的终端节点服务。
-   server\_type：创建的终端节点服务的后端资源类型。例如“VM”，表示创建云服务器类型的终端节点服务。
-   ports.client\_port：终端节点提供给用户，作为访问终端节点服务的端口。
-   ports.server\_port：终端节点服务绑定了后端资源，作为提供服务的端口。
-   ports.protocol：端口映射协议。

## 创建终端节点<a name="section545825316317"></a>

在本示例中，创建了一个终端节点，且支持自动创建内网域名。

>![](public_sys-resources/icon-note.gif) **说明：** 
>创建终端节点前请先获取创建的必要信息，如终端节点所在的VPC的ID、Subnet ID和上一步创建返回的终端节点服务ID等，详情请参考[创建终端节点](创建终端节点.md)。

```
{ 
  "subnet_id": "4189d3c2-8882-4871-a3c2-d380272eed81",
  "vpc_id": "4189d3c2-8882-4871-a3c2-d380272eed82",
  "endpoint_service_id":"4189d3c2-8882-4871-a3c2-d380272eed83",
  "enable_dns":true
} 
```

-   subnet\_id：终端节点所在VPC的子网ID
-   vpc\_id：终端节点所在的VPC的ID。
-   endpoint\_service\_id：终端节点服务的ID。
-   enable\_dns：是否为终端节点创建内网域名。例如“true”，表示创建内网域名。

创建完成之后，终端节点所在的VPC内的实例可使用该终端节点访问ID为“4189d3c2-8882-4871-a3c2-d380272eed83”的终端节点服务。

