# 修改网关型终端节点policy<a name="UpdateEndpointPolicy"></a>

## 功能介绍<a name="section28361055487"></a>

功能介绍 修改网关型终端节点policy。

## 调试<a name="section283705513812"></a>

您可以在[API Explorer](https://apiexplorer.developer.huaweicloud.com/apiexplorer/doc?product=VPCEP&api=UpdateEndpointPolicy)中调试该接口，支持自动认证鉴权。API Explorer可以自动生成SDK代码示例，并提供SDK代码示例调试功能。

## URI<a name="section5837855183"></a>

PUT /v1/\{project\_id\}/vpc-endpoints/\{vpc\_endpoint\_id\}/policy

**表 1**  路径参数

<a name="table3839175518819"></a>
<table><thead align="left"><tr id="row583818554818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.1"><p id="p1983975510812"><a name="p1983975510812"></a><a name="p1983975510812"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="p184019551987"><a name="p184019551987"></a><a name="p184019551987"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.3"><p id="p3840155510818"><a name="p3840155510818"></a><a name="p3840155510818"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p68409551810"><a name="p68409551810"></a><a name="p68409551810"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1883819555811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p168405551685"><a name="p168405551685"></a><a name="p168405551685"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p484010556813"><a name="p484010556813"></a><a name="p484010556813"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p1484175518816"><a name="p1484175518816"></a><a name="p1484175518816"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p484115514815"><a name="p484115514815"></a><a name="p484115514815"></a>项目ID</p>
<p id="p98421355989"><a name="p98421355989"></a><a name="p98421355989"></a>最小长度：<strong id="b48421755582"><a name="b48421755582"></a><a name="b48421755582"></a>1</strong></p>
<p id="p484211551283"><a name="p484211551283"></a><a name="p484211551283"></a>最大长度：<strong id="b18421255789"><a name="b18421255789"></a><a name="b18421255789"></a>64</strong></p>
</td>
</tr>
<tr id="row108391551584"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p68421556812"><a name="p68421556812"></a><a name="p68421556812"></a>vpc_endpoint_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p58423552820"><a name="p58423552820"></a><a name="p58423552820"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p178431551483"><a name="p178431551483"></a><a name="p178431551483"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p188431551283"><a name="p188431551283"></a><a name="p188431551283"></a>终端节点的ID。</p>
<p id="p58431551781"><a name="p58431551781"></a><a name="p58431551781"></a>最小长度：<strong id="b0843105514813"><a name="b0843105514813"></a><a name="b0843105514813"></a>1</strong></p>
<p id="p5843555889"><a name="p5843555889"></a><a name="p5843555889"></a>最大长度：<strong id="b484314553813"><a name="b484314553813"></a><a name="b484314553813"></a>64</strong></p>
</td>
</tr>
</tbody>
</table>

## 请求参数<a name="section2843255482"></a>

**表 2**  请求Header参数

<a name="HeaderParameter"></a>
<table><thead align="left"><tr id="row18446554820"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.1"><p id="p5845855288"><a name="p5845855288"></a><a name="p5845855288"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="p2845195512814"><a name="p2845195512814"></a><a name="p2845195512814"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.3"><p id="p168462055384"><a name="p168462055384"></a><a name="p168462055384"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p1084615553817"><a name="p1084615553817"></a><a name="p1084615553817"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1584485515813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p3846195513817"><a name="p3846195513817"></a><a name="p3846195513817"></a>X-Auth-Token</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p78461455581"><a name="p78461455581"></a><a name="p78461455581"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p128477556810"><a name="p128477556810"></a><a name="p128477556810"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p138472055883"><a name="p138472055883"></a><a name="p138472055883"></a>用户Token。通过调用IAM服务获取用户Token接口获取(响应消息头中X-Subject-Token的值)。</p>
<p id="p98474550815"><a name="p98474550815"></a><a name="p98474550815"></a>最小长度：<strong id="b984713552810"><a name="b984713552810"></a><a name="b984713552810"></a>1</strong></p>
<p id="p1084719551782"><a name="p1084719551782"></a><a name="p1084719551782"></a>最大长度：<strong id="b1384714551980"><a name="b1384714551980"></a><a name="b1384714551980"></a>2048</strong></p>
</td>
</tr>
<tr id="row884445518815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p138481255382"><a name="p138481255382"></a><a name="p138481255382"></a>Content-Type</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p1584817557811"><a name="p1584817557811"></a><a name="p1584817557811"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p08481055881"><a name="p08481055881"></a><a name="p08481055881"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p3849155185"><a name="p3849155185"></a><a name="p3849155185"></a>发送的实体的MIME类型。推荐用户默认使用application/json， 如果API是对象、镜像上传等接口，媒体类型可按照流类型的不同进行确定。</p>
<p id="p16849145510816"><a name="p16849145510816"></a><a name="p16849145510816"></a>最小长度：<strong id="b584911551286"><a name="b584911551286"></a><a name="b584911551286"></a>1</strong></p>
<p id="p15849165514819"><a name="p15849165514819"></a><a name="p15849165514819"></a>最大长度：<strong id="b1884917551586"><a name="b1884917551586"></a><a name="b1884917551586"></a>64</strong></p>
</td>
</tr>
</tbody>
</table>

**表 3**  请求Body参数

<a name="request_UpdateEndpointPolicyRequestBody"></a>
<table><thead align="left"><tr id="row128509558819"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.1"><p id="p1785111551786"><a name="p1785111551786"></a><a name="p1785111551786"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="p11851105514811"><a name="p11851105514811"></a><a name="p11851105514811"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.3"><p id="p285117552814"><a name="p285117552814"></a><a name="p285117552814"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p19851955089"><a name="p19851955089"></a><a name="p19851955089"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row108509551184"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p785105518812"><a name="p785105518812"></a><a name="p785105518812"></a>policy_statement</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p4852135517813"><a name="p4852135517813"></a><a name="p4852135517813"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p78526550810"><a name="p78526550810"></a><a name="p78526550810"></a>Array of <a href="#request_PolicyStatement">PolicyStatement</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p19852105514815"><a name="p19852105514815"></a><a name="p19852105514815"></a>只涉及开启双端固定的网关型终端节点</p>
</td>
</tr>
</tbody>
</table>

**表 4**  PolicyStatement

<a name="request_PolicyStatement"></a>
<table><thead align="left"><tr id="row198531755384"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.1"><p id="p14854145512816"><a name="p14854145512816"></a><a name="p14854145512816"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="p208541555489"><a name="p208541555489"></a><a name="p208541555489"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.3"><p id="p188541555287"><a name="p188541555287"></a><a name="p188541555287"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p1285415557810"><a name="p1285415557810"></a><a name="p1285415557810"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row385345520818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p19855185519819"><a name="p19855185519819"></a><a name="p19855185519819"></a>Effect</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p985519551483"><a name="p985519551483"></a><a name="p985519551483"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p188551855288"><a name="p188551855288"></a><a name="p188551855288"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p885585510818"><a name="p885585510818"></a><a name="p885585510818"></a>允许或拒绝，控制访问权限</p>
</td>
</tr>
<tr id="row14853255989"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p17856355988"><a name="p17856355988"></a><a name="p17856355988"></a>Action</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p188563552815"><a name="p188563552815"></a><a name="p188563552815"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p14856155516811"><a name="p14856155516811"></a><a name="p14856155516811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p1185619554819"><a name="p1185619554819"></a><a name="p1185619554819"></a>obs访问权限</p>
</td>
</tr>
<tr id="row2085395510817"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p98561755388"><a name="p98561755388"></a><a name="p98561755388"></a>Resource</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p28575551981"><a name="p28575551981"></a><a name="p28575551981"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p185885510819"><a name="p185885510819"></a><a name="p185885510819"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p78588550813"><a name="p78588550813"></a><a name="p78588550813"></a>obs对象</p>
</td>
</tr>
</tbody>
</table>

## 响应参数<a name="section1785920551818"></a>

**状态码： 200**

**表 5**  响应Body参数

<a name="response_EndpointResp"></a>
<table><thead align="left"><tr id="row18609557812"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p48634551583"><a name="p48634551583"></a><a name="p48634551583"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p886311551986"><a name="p886311551986"></a><a name="p886311551986"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1186314557815"><a name="p1186314557815"></a><a name="p1186314557815"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row17860955582"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p286410551889"><a name="p286410551889"></a><a name="p286410551889"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p686415551289"><a name="p686415551289"></a><a name="p686415551289"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1086413551588"><a name="p1086413551588"></a><a name="p1086413551588"></a>终端节点的ID，唯一标识。</p>
</td>
</tr>
<tr id="row78607554813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p986485515813"><a name="p986485515813"></a><a name="p986485515813"></a>service_type</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p7865455186"><a name="p7865455186"></a><a name="p7865455186"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p78651955386"><a name="p78651955386"></a><a name="p78651955386"></a>终端节点连接的终端节点服务类型。 ● gataway：由运维人员配置。用户无需创建，可直接使用。 ● interface：包括运维人员配置的云服务和用户自己创建的私有服务。 其中，运维人员配置的云服务无需创建，用户可直接使用。 您可以通过查询公共终端节点服务列表， 查看由运维人员配置的所有用户可见且可连接的终端节点服务， 并通过创建终端节点服务创建Interface类型的终端节点服务。</p>
</td>
</tr>
<tr id="row128608557814"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p38654551984"><a name="p38654551984"></a><a name="p38654551984"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p168662551482"><a name="p168662551482"></a><a name="p168662551482"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1887205517815"><a name="p1887205517815"></a><a name="p1887205517815"></a>终端节点的连接状态。 ● pendingAcceptance：待接受 ● creating：创建中 ● accepted：已接受 ● failed：失败</p>
</td>
</tr>
<tr id="row10860185519820"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p16873135510814"><a name="p16873135510814"></a><a name="p16873135510814"></a>active_status</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p187318557816"><a name="p187318557816"></a><a name="p187318557816"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p18739551888"><a name="p18739551888"></a><a name="p18739551888"></a>帐号状态。 ● frozen：冻结 ● active：解冻</p>
</td>
</tr>
<tr id="row1786018551285"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p58731455282"><a name="p58731455282"></a><a name="p58731455282"></a>endpoint_service_name</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p6874205512810"><a name="p6874205512810"></a><a name="p6874205512810"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p13874205517814"><a name="p13874205517814"></a><a name="p13874205517814"></a>终端节点服务的名称。</p>
</td>
</tr>
<tr id="row1886075516817"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p13874655782"><a name="p13874655782"></a><a name="p13874655782"></a>marker_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p38745551985"><a name="p38745551985"></a><a name="p38745551985"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p188751553818"><a name="p188751553818"></a><a name="p188751553818"></a>终端节点的报文标识。</p>
</td>
</tr>
<tr id="row3860155515810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p108759551283"><a name="p108759551283"></a><a name="p108759551283"></a>endpoint_service_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p18875155512817"><a name="p18875155512817"></a><a name="p18875155512817"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p138751155688"><a name="p138751155688"></a><a name="p138751155688"></a>终端节点服务的ID。</p>
</td>
</tr>
<tr id="row08601855088"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p2087517551780"><a name="p2087517551780"></a><a name="p2087517551780"></a>enable_dns</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p13876355488"><a name="p13876355488"></a><a name="p13876355488"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p14876755089"><a name="p14876755089"></a><a name="p14876755089"></a>是否创建域名。 ● true：创建域名 ● false：不创建域名 说明 当创建连接gateway类型终端节点服务的终端节点时， “enable_dns”设置为true或者false，均不创建域名。</p>
</td>
</tr>
<tr id="row08618555812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p48762552813"><a name="p48762552813"></a><a name="p48762552813"></a>dns_names</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p12876055680"><a name="p12876055680"></a><a name="p12876055680"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p12876195510813"><a name="p12876195510813"></a><a name="p12876195510813"></a>访问所连接的终端节点服务的域名。 当“enable_dns”为true时，该参数可见。</p>
</td>
</tr>
<tr id="row1986125513814"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p12877175510814"><a name="p12877175510814"></a><a name="p12877175510814"></a>ip</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1587755517814"><a name="p1587755517814"></a><a name="p1587755517814"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1087719552087"><a name="p1087719552087"></a><a name="p1087719552087"></a>访问所连接的终端节点服务的IP。 仅当同时满足如下条件时，返回该参数： 当查询连接interface类型终端节点服务的终端节点时。 终端节点服务启用“连接审批”功能，且已经“接受”连接审批。 “status”可以是“accepted”或者“rejected（仅支持“接受”连接审批后再“拒绝”的情况）”。</p>
</td>
</tr>
<tr id="row198612552811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1387715514816"><a name="p1387715514816"></a><a name="p1387715514816"></a>vpc_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1487835517813"><a name="p1487835517813"></a><a name="p1487835517813"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p198780551587"><a name="p198780551587"></a><a name="p198780551587"></a>终端节点所在的VPC的ID。</p>
</td>
</tr>
<tr id="row28611655080"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1587875515812"><a name="p1587875515812"></a><a name="p1587875515812"></a>subnet_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p8878655888"><a name="p8878655888"></a><a name="p8878655888"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p787910551588"><a name="p787910551588"></a><a name="p787910551588"></a>vpc_id对应VPC下已创建的网络（network）的ID，UUID格式。</p>
</td>
</tr>
<tr id="row1186145513815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1687918551483"><a name="p1687918551483"></a><a name="p1687918551483"></a>created_at</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p087915551813"><a name="p087915551813"></a><a name="p087915551813"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1588011551089"><a name="p1588011551089"></a><a name="p1588011551089"></a>终端节点的创建时间。 采用UTC时间格式，格式为：YYYY-MM-DDTHH:MM:SSZ</p>
</td>
</tr>
<tr id="row138619551889"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p78803551782"><a name="p78803551782"></a><a name="p78803551782"></a>updated_at</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p2880255485"><a name="p2880255485"></a><a name="p2880255485"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p88801555588"><a name="p88801555588"></a><a name="p88801555588"></a>终端节点的更新时间。 采用UTC时间格式，格式为：YYYY-MM-DDTHH:MM:SSZ</p>
</td>
</tr>
<tr id="row9861155515815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p088012551180"><a name="p088012551180"></a><a name="p088012551180"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p188185512816"><a name="p188185512816"></a><a name="p188185512816"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p888185517813"><a name="p888185517813"></a><a name="p888185517813"></a>项目ID，获取方法请参见获取项目ID。</p>
</td>
</tr>
<tr id="row286185516810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p18818550814"><a name="p18818550814"></a><a name="p18818550814"></a>tags</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1588116550811"><a name="p1588116550811"></a><a name="p1588116550811"></a>Array of <a href="#response_TagList">TagList</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p188220551816"><a name="p188220551816"></a><a name="p188220551816"></a>标签列表，没有标签默认为空数组。</p>
</td>
</tr>
<tr id="row10861105514811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p4882955588"><a name="p4882955588"></a><a name="p4882955588"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p128825553812"><a name="p128825553812"></a><a name="p128825553812"></a>Array of <a href="#response_QueryError">QueryError</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p10882155786"><a name="p10882155786"></a><a name="p10882155786"></a>错误信息。 当终端节点状态异常，即“status”的值为“failed”时，会返回该字段。</p>
</td>
</tr>
<tr id="row78615551081"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p11883185518819"><a name="p11883185518819"></a><a name="p11883185518819"></a>whitelist</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1488355515819"><a name="p1488355515819"></a><a name="p1488355515819"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p19883125511814"><a name="p19883125511814"></a><a name="p19883125511814"></a>控制访问终端节点的白名单。 若未创建，则返回空列表。 创建连接Interface类型终端节点服务的终端节点时，显示此参数。</p>
</td>
</tr>
<tr id="row168625551783"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p178834555813"><a name="p178834555813"></a><a name="p178834555813"></a>enable_whitelist</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p8883165511815"><a name="p8883165511815"></a><a name="p8883165511815"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1488420551786"><a name="p1488420551786"></a><a name="p1488420551786"></a>是否开启网络ACL隔离。 ● true：开启网络ACL隔离 ● false：不开启网络ACL隔离 若未指定，则返回false。 创建连接Interface类型终端节点服务的终端节点时，显示此参数。</p>
</td>
</tr>
<tr id="row98622055983"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p138847551813"><a name="p138847551813"></a><a name="p138847551813"></a>routetables</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p48849551584"><a name="p48849551584"></a><a name="p48849551584"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p10884145518811"><a name="p10884145518811"></a><a name="p10884145518811"></a>路由表ID列表。 若未指定，返回默认VPC下路由表ID。 创建连接Gateway类型终端节点服务的终端节点时，显示此参数。</p>
</td>
</tr>
<tr id="row4862955782"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p688575511820"><a name="p688575511820"></a><a name="p688575511820"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p488585512812"><a name="p488585512812"></a><a name="p488585512812"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p78859551086"><a name="p78859551086"></a><a name="p78859551086"></a>描述字段，支持中英文字母、数字等字符，不支持“&lt;”或“&gt;”字符。</p>
</td>
</tr>
<tr id="row118621556811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p288512551784"><a name="p288512551784"></a><a name="p288512551784"></a>policy_statement</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p168851555684"><a name="p168851555684"></a><a name="p168851555684"></a>Array of <a href="#response_PolicyStatement">PolicyStatement</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p688611551587"><a name="p688611551587"></a><a name="p688611551587"></a>只涉及开启双端固定的网关型终端节点，响应体展示此字段</p>
</td>
</tr>
<tr id="row128621555984"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p68861555984"><a name="p68861555984"></a><a name="p68861555984"></a>endpoint_pool_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p208866551085"><a name="p208866551085"></a><a name="p208866551085"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p19887105518811"><a name="p19887105518811"></a><a name="p19887105518811"></a>终端节点相关联的Pood的ID</p>
</td>
</tr>
<tr id="row19862185520810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p888705516814"><a name="p888705516814"></a><a name="p888705516814"></a>public_border_group</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p118887551183"><a name="p118887551183"></a><a name="p118887551183"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1588818558810"><a name="p1588818558810"></a><a name="p1588818558810"></a>终端节点关联的Public Border Group信息，只有当终端节点和边缘Pool相关联时才会返回改字段</p>
</td>
</tr>
</tbody>
</table>

**表 6**  TagList

<a name="response_TagList"></a>
<table><thead align="left"><tr id="row208883553818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p28900551683"><a name="p28900551683"></a><a name="p28900551683"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p689012551985"><a name="p689012551985"></a><a name="p689012551985"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1289018553815"><a name="p1289018553815"></a><a name="p1289018553815"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row98891055580"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1589018559815"><a name="p1589018559815"></a><a name="p1589018559815"></a>key</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p6891135518819"><a name="p6891135518819"></a><a name="p6891135518819"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p789116551889"><a name="p789116551889"></a><a name="p789116551889"></a>键。 最大长度36个unicode字符。 key不能为空。不能包含“=”、“*”、“&lt;”、“&gt;”、“\”、“,”、“|”和“/”，且首尾字符不能为空格。</p>
<p id="p1989185514813"><a name="p1989185514813"></a><a name="p1989185514813"></a>最小长度：<strong id="b1789115556814"><a name="b1789115556814"></a><a name="b1789115556814"></a>1</strong></p>
<p id="p158911551581"><a name="p158911551581"></a><a name="p158911551581"></a>最大长度：<strong id="b148924557810"><a name="b148924557810"></a><a name="b148924557810"></a>36</strong></p>
</td>
</tr>
<tr id="row1388913559820"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p13892165518818"><a name="p13892165518818"></a><a name="p13892165518818"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p189218551882"><a name="p189218551882"></a><a name="p189218551882"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p118921655482"><a name="p118921655482"></a><a name="p118921655482"></a>值。 每个值最大长度43个unicode字符，可以为空字符串。 不能包含“=”、“*”、“&lt;”、“&gt;”、“\”、“,”、“|”和“/”，且首尾字符不能为空格。</p>
<p id="p1289213551883"><a name="p1289213551883"></a><a name="p1289213551883"></a>最小长度：<strong id="b4893655683"><a name="b4893655683"></a><a name="b4893655683"></a>1</strong></p>
<p id="p108933553813"><a name="p108933553813"></a><a name="p108933553813"></a>最大长度：<strong id="b1689319559814"><a name="b1689319559814"></a><a name="b1689319559814"></a>43</strong></p>
</td>
</tr>
</tbody>
</table>

**表 7**  QueryError

<a name="response_QueryError"></a>
<table><thead align="left"><tr id="row1989316559819"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p158942552085"><a name="p158942552085"></a><a name="p158942552085"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p389415550820"><a name="p389415550820"></a><a name="p389415550820"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p58951655381"><a name="p58951655381"></a><a name="p58951655381"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row4893155515817"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p98951755288"><a name="p98951755288"></a><a name="p98951755288"></a>error_code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p28950551488"><a name="p28950551488"></a><a name="p28950551488"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p58951255686"><a name="p58951255686"></a><a name="p58951255686"></a>错误编码。</p>
</td>
</tr>
<tr id="row789335512815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p158961755985"><a name="p158961755985"></a><a name="p158961755985"></a>error_message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p188963558810"><a name="p188963558810"></a><a name="p188963558810"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p4896855084"><a name="p4896855084"></a><a name="p4896855084"></a>错误信息。</p>
</td>
</tr>
</tbody>
</table>

**表 8**  PolicyStatement

<a name="response_PolicyStatement"></a>
<table><thead align="left"><tr id="row1089715558812"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p189718551487"><a name="p189718551487"></a><a name="p189718551487"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p78987551382"><a name="p78987551382"></a><a name="p78987551382"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p489815519819"><a name="p489815519819"></a><a name="p489815519819"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1089711551885"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p108981255285"><a name="p108981255285"></a><a name="p108981255285"></a>Effect</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p789911559815"><a name="p789911559815"></a><a name="p789911559815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p168999551986"><a name="p168999551986"></a><a name="p168999551986"></a>允许或拒绝，控制访问权限</p>
</td>
</tr>
<tr id="row889711553811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p289914551987"><a name="p289914551987"></a><a name="p289914551987"></a>Action</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p289920558811"><a name="p289920558811"></a><a name="p289920558811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p28991155186"><a name="p28991155186"></a><a name="p28991155186"></a>obs访问权限</p>
</td>
</tr>
<tr id="row1689716554816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1090045510816"><a name="p1090045510816"></a><a name="p1090045510816"></a>Resource</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1290012551088"><a name="p1290012551088"></a><a name="p1290012551088"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p690015514816"><a name="p690015514816"></a><a name="p690015514816"></a>obs对象</p>
</td>
</tr>
</tbody>
</table>

**状态码： 400**

**表 9**  响应Body参数

<a name="response_FailedRsp"></a>
<table><thead align="left"><tr id="row29016555812"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1902955881"><a name="p1902955881"></a><a name="p1902955881"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p890295510810"><a name="p890295510810"></a><a name="p890295510810"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p16902135519813"><a name="p16902135519813"></a><a name="p16902135519813"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1190105518811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1390214554813"><a name="p1390214554813"></a><a name="p1390214554813"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p39031355884"><a name="p39031355884"></a><a name="p39031355884"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1903255588"><a name="p1903255588"></a><a name="p1903255588"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 10**  Error

<a name="response_Error"></a>
<table><thead align="left"><tr id="row29046551685"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1485956983"><a name="p1485956983"></a><a name="p1485956983"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1048519561814"><a name="p1048519561814"></a><a name="p1048519561814"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p44851656388"><a name="p44851656388"></a><a name="p44851656388"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row0904855387"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p3485175616813"><a name="p3485175616813"></a><a name="p3485175616813"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p94850561189"><a name="p94850561189"></a><a name="p94850561189"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p648511561780"><a name="p648511561780"></a><a name="p648511561780"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row14904155517814"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p14851956683"><a name="p14851956683"></a><a name="p14851956683"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p248515617820"><a name="p248515617820"></a><a name="p248515617820"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p14851956386"><a name="p14851956386"></a><a name="p14851956386"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 401**

**表 11**  响应Body参数

<a name="table69063551786"></a>
<table><thead align="left"><tr id="row17906105519818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p848516561816"><a name="p848516561816"></a><a name="p848516561816"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1448514564811"><a name="p1448514564811"></a><a name="p1448514564811"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p24860561386"><a name="p24860561386"></a><a name="p24860561386"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1590775520816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p2048620561580"><a name="p2048620561580"></a><a name="p2048620561580"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p194862561486"><a name="p194862561486"></a><a name="p194862561486"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p16486456780"><a name="p16486456780"></a><a name="p16486456780"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 12**  Error

<a name="table1490875520813"></a>
<table><thead align="left"><tr id="row390919555818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p7488165614811"><a name="p7488165614811"></a><a name="p7488165614811"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p204881856089"><a name="p204881856089"></a><a name="p204881856089"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p8488175616812"><a name="p8488175616812"></a><a name="p8488175616812"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row2909135517817"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p648818566811"><a name="p648818566811"></a><a name="p648818566811"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p194884561985"><a name="p194884561985"></a><a name="p194884561985"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1348815563812"><a name="p1348815563812"></a><a name="p1348815563812"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row13909195514813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1348805612812"><a name="p1348805612812"></a><a name="p1348805612812"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p24882566815"><a name="p24882566815"></a><a name="p24882566815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1648812561482"><a name="p1648812561482"></a><a name="p1648812561482"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 403**

**表 13**  响应Body参数

<a name="table2091114551482"></a>
<table><thead align="left"><tr id="row109111355280"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p84897568810"><a name="p84897568810"></a><a name="p84897568810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p164891656980"><a name="p164891656980"></a><a name="p164891656980"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p14895561683"><a name="p14895561683"></a><a name="p14895561683"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1091113551385"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p248911561989"><a name="p248911561989"></a><a name="p248911561989"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1348915561588"><a name="p1348915561588"></a><a name="p1348915561588"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p44892561483"><a name="p44892561483"></a><a name="p44892561483"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 14**  Error

<a name="table12913165520816"></a>
<table><thead align="left"><tr id="row1491316551383"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p154891856187"><a name="p154891856187"></a><a name="p154891856187"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1048910561789"><a name="p1048910561789"></a><a name="p1048910561789"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p3489105618814"><a name="p3489105618814"></a><a name="p3489105618814"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row109131551789"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1489956580"><a name="p1489956580"></a><a name="p1489956580"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p4489135616816"><a name="p4489135616816"></a><a name="p4489135616816"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1489256787"><a name="p1489256787"></a><a name="p1489256787"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row59137551811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p134899568818"><a name="p134899568818"></a><a name="p134899568818"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p19489556582"><a name="p19489556582"></a><a name="p19489556582"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p84891456980"><a name="p84891456980"></a><a name="p84891456980"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 404**

**表 15**  响应Body参数

<a name="table19166551388"></a>
<table><thead align="left"><tr id="row10916175517818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p649014561982"><a name="p649014561982"></a><a name="p649014561982"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p8490145614810"><a name="p8490145614810"></a><a name="p8490145614810"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p249016561881"><a name="p249016561881"></a><a name="p249016561881"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row159165551989"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1249013561819"><a name="p1249013561819"></a><a name="p1249013561819"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p54908566813"><a name="p54908566813"></a><a name="p54908566813"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p184901756889"><a name="p184901756889"></a><a name="p184901756889"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 16**  Error

<a name="table13918205515819"></a>
<table><thead align="left"><tr id="row1691815551785"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p849019561685"><a name="p849019561685"></a><a name="p849019561685"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p54905560817"><a name="p54905560817"></a><a name="p54905560817"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p749019561784"><a name="p749019561784"></a><a name="p749019561784"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row16919165511818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p8490456284"><a name="p8490456284"></a><a name="p8490456284"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p19490756886"><a name="p19490756886"></a><a name="p19490756886"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1449014561187"><a name="p1449014561187"></a><a name="p1449014561187"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row2091945514812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p184902561582"><a name="p184902561582"></a><a name="p184902561582"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p134908561587"><a name="p134908561587"></a><a name="p134908561587"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p94903561881"><a name="p94903561881"></a><a name="p94903561881"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 405**

**表 17**  响应Body参数

<a name="table16921195516817"></a>
<table><thead align="left"><tr id="row119216557813"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p15490175617815"><a name="p15490175617815"></a><a name="p15490175617815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p449014564813"><a name="p449014564813"></a><a name="p449014564813"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p34901656189"><a name="p34901656189"></a><a name="p34901656189"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1892211551581"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p84914561489"><a name="p84914561489"></a><a name="p84914561489"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p8491456982"><a name="p8491456982"></a><a name="p8491456982"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p449113562081"><a name="p449113562081"></a><a name="p449113562081"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 18**  Error

<a name="table139231055185"></a>
<table><thead align="left"><tr id="row179231555889"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p34917561082"><a name="p34917561082"></a><a name="p34917561082"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p14912561482"><a name="p14912561482"></a><a name="p14912561482"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p849115616819"><a name="p849115616819"></a><a name="p849115616819"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row119244551989"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p154919567811"><a name="p154919567811"></a><a name="p154919567811"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1849145612811"><a name="p1849145612811"></a><a name="p1849145612811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p749155610816"><a name="p749155610816"></a><a name="p749155610816"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row5924955583"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p54911456282"><a name="p54911456282"></a><a name="p54911456282"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p10491256183"><a name="p10491256183"></a><a name="p10491256183"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p849117565820"><a name="p849117565820"></a><a name="p849117565820"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 406**

**表 19**  响应Body参数

<a name="table159262551184"></a>
<table><thead align="left"><tr id="row49261055581"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1549113561481"><a name="p1549113561481"></a><a name="p1549113561481"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p149113561583"><a name="p149113561583"></a><a name="p149113561583"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p154913568819"><a name="p154913568819"></a><a name="p154913568819"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row89263557812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p20491056285"><a name="p20491056285"></a><a name="p20491056285"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1149118561486"><a name="p1149118561486"></a><a name="p1149118561486"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1449114565813"><a name="p1449114565813"></a><a name="p1449114565813"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 20**  Error

<a name="table492812553819"></a>
<table><thead align="left"><tr id="row29281055981"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p949217562818"><a name="p949217562818"></a><a name="p949217562818"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p154928561488"><a name="p154928561488"></a><a name="p154928561488"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p14492125618816"><a name="p14492125618816"></a><a name="p14492125618816"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row199281955182"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p104926563815"><a name="p104926563815"></a><a name="p104926563815"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p04921356382"><a name="p04921356382"></a><a name="p04921356382"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1249245613811"><a name="p1249245613811"></a><a name="p1249245613811"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row17928155512820"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p54923561819"><a name="p54923561819"></a><a name="p54923561819"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p24921856481"><a name="p24921856481"></a><a name="p24921856481"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p74928561819"><a name="p74928561819"></a><a name="p74928561819"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 407**

**表 21**  响应Body参数

<a name="table89302055589"></a>
<table><thead align="left"><tr id="row69303551686"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p549215561084"><a name="p549215561084"></a><a name="p549215561084"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p749210562081"><a name="p749210562081"></a><a name="p749210562081"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1449219565811"><a name="p1449219565811"></a><a name="p1449219565811"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row149313555816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1249285611817"><a name="p1249285611817"></a><a name="p1249285611817"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p849211569814"><a name="p849211569814"></a><a name="p849211569814"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p449211562080"><a name="p449211562080"></a><a name="p449211562080"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 22**  Error

<a name="table19932155987"></a>
<table><thead align="left"><tr id="row1193213553810"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p6492135616812"><a name="p6492135616812"></a><a name="p6492135616812"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p14922561283"><a name="p14922561283"></a><a name="p14922561283"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p134921569812"><a name="p134921569812"></a><a name="p134921569812"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row493216551186"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p164931561188"><a name="p164931561188"></a><a name="p164931561188"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p8493256784"><a name="p8493256784"></a><a name="p8493256784"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p549385613810"><a name="p549385613810"></a><a name="p549385613810"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row179331655886"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p349315565810"><a name="p349315565810"></a><a name="p349315565810"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p15493205611815"><a name="p15493205611815"></a><a name="p15493205611815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p84934563812"><a name="p84934563812"></a><a name="p84934563812"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 408**

**表 23**  响应Body参数

<a name="table9935185513818"></a>
<table><thead align="left"><tr id="row69354553815"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p154932567810"><a name="p154932567810"></a><a name="p154932567810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p44936561483"><a name="p44936561483"></a><a name="p44936561483"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p194931256589"><a name="p194931256589"></a><a name="p194931256589"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row13935105511819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p149317561686"><a name="p149317561686"></a><a name="p149317561686"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p54935564811"><a name="p54935564811"></a><a name="p54935564811"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p104938561487"><a name="p104938561487"></a><a name="p104938561487"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 24**  Error

<a name="table6936755686"></a>
<table><thead align="left"><tr id="row129372551080"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p8493115612817"><a name="p8493115612817"></a><a name="p8493115612817"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p84938561881"><a name="p84938561881"></a><a name="p84938561881"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1493135614813"><a name="p1493135614813"></a><a name="p1493135614813"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row89372554819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p19493185619813"><a name="p19493185619813"></a><a name="p19493185619813"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1149312561180"><a name="p1149312561180"></a><a name="p1149312561180"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p449355619818"><a name="p449355619818"></a><a name="p449355619818"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row59371655388"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p249310564817"><a name="p249310564817"></a><a name="p249310564817"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p84949560818"><a name="p84949560818"></a><a name="p84949560818"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p44947561789"><a name="p44947561789"></a><a name="p44947561789"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 409**

**表 25**  响应Body参数

<a name="table1893914558818"></a>
<table><thead align="left"><tr id="row1939555487"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p849410561183"><a name="p849410561183"></a><a name="p849410561183"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p124947564813"><a name="p124947564813"></a><a name="p124947564813"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p104941356884"><a name="p104941356884"></a><a name="p104941356884"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row109409554815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p114946561984"><a name="p114946561984"></a><a name="p114946561984"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p184941156289"><a name="p184941156289"></a><a name="p184941156289"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p34941556184"><a name="p34941556184"></a><a name="p34941556184"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 26**  Error

<a name="table119414551081"></a>
<table><thead align="left"><tr id="row9941195513813"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p134942564814"><a name="p134942564814"></a><a name="p134942564814"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p184941556786"><a name="p184941556786"></a><a name="p184941556786"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p84948560815"><a name="p84948560815"></a><a name="p84948560815"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row39422554817"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p104945562817"><a name="p104945562817"></a><a name="p104945562817"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p12494105610812"><a name="p12494105610812"></a><a name="p12494105610812"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1049414562820"><a name="p1049414562820"></a><a name="p1049414562820"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row1942195516814"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p64944561686"><a name="p64944561686"></a><a name="p64944561686"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p144946562080"><a name="p144946562080"></a><a name="p144946562080"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1849415561281"><a name="p1849415561281"></a><a name="p1849415561281"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 500**

**表 27**  响应Body参数

<a name="table1794415554811"></a>
<table><thead align="left"><tr id="row8944135513817"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1049512562810"><a name="p1049512562810"></a><a name="p1049512562810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1249519561684"><a name="p1249519561684"></a><a name="p1249519561684"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p549525611811"><a name="p549525611811"></a><a name="p549525611811"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row29444551985"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p449515561286"><a name="p449515561286"></a><a name="p449515561286"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p14958566817"><a name="p14958566817"></a><a name="p14958566817"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p12495205613817"><a name="p12495205613817"></a><a name="p12495205613817"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 28**  Error

<a name="table19945185518811"></a>
<table><thead align="left"><tr id="row09461055387"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p10495135619815"><a name="p10495135619815"></a><a name="p10495135619815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p154951056587"><a name="p154951056587"></a><a name="p154951056587"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p64955561983"><a name="p64955561983"></a><a name="p64955561983"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row2094635516819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p20495185610817"><a name="p20495185610817"></a><a name="p20495185610817"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p2495256383"><a name="p2495256383"></a><a name="p2495256383"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p84957561380"><a name="p84957561380"></a><a name="p84957561380"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row994615553815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p24956561088"><a name="p24956561088"></a><a name="p24956561088"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p4495145612817"><a name="p4495145612817"></a><a name="p4495145612817"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1349516567810"><a name="p1349516567810"></a><a name="p1349516567810"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 501**

**表 29**  响应Body参数

<a name="table89486551882"></a>
<table><thead align="left"><tr id="row15949145510818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1249512564814"><a name="p1249512564814"></a><a name="p1249512564814"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p14951356881"><a name="p14951356881"></a><a name="p14951356881"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p149595612817"><a name="p149595612817"></a><a name="p149595612817"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1294925512818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1496175611811"><a name="p1496175611811"></a><a name="p1496175611811"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p19496125615816"><a name="p19496125615816"></a><a name="p19496125615816"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p74962561486"><a name="p74962561486"></a><a name="p74962561486"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 30**  Error

<a name="table19951155516817"></a>
<table><thead align="left"><tr id="row39518552818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p12496155613813"><a name="p12496155613813"></a><a name="p12496155613813"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p04965561884"><a name="p04965561884"></a><a name="p04965561884"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p134961756187"><a name="p134961756187"></a><a name="p134961756187"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row79511055888"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1249617561788"><a name="p1249617561788"></a><a name="p1249617561788"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p14967562819"><a name="p14967562819"></a><a name="p14967562819"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1649618569812"><a name="p1649618569812"></a><a name="p1649618569812"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row189516551984"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p124967561982"><a name="p124967561982"></a><a name="p124967561982"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p154967565811"><a name="p154967565811"></a><a name="p154967565811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1149618565812"><a name="p1149618565812"></a><a name="p1149618565812"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 502**

**表 31**  响应Body参数

<a name="table1295315513816"></a>
<table><thead align="left"><tr id="row1295415513812"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p8496145620816"><a name="p8496145620816"></a><a name="p8496145620816"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1049620560820"><a name="p1049620560820"></a><a name="p1049620560820"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p184961356383"><a name="p184961356383"></a><a name="p184961356383"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1495412552818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p54961356887"><a name="p54961356887"></a><a name="p54961356887"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p349675615819"><a name="p349675615819"></a><a name="p349675615819"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p94961056984"><a name="p94961056984"></a><a name="p94961056984"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 32**  Error

<a name="table795625511811"></a>
<table><thead align="left"><tr id="row195617551389"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p54974567811"><a name="p54974567811"></a><a name="p54974567811"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p14497356885"><a name="p14497356885"></a><a name="p14497356885"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p549785613811"><a name="p549785613811"></a><a name="p549785613811"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row11956555986"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p04979561082"><a name="p04979561082"></a><a name="p04979561082"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p449745618811"><a name="p449745618811"></a><a name="p449745618811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1649755611810"><a name="p1649755611810"></a><a name="p1649755611810"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row1495619552813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p44971456687"><a name="p44971456687"></a><a name="p44971456687"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p44972056885"><a name="p44972056885"></a><a name="p44972056885"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p749713568820"><a name="p749713568820"></a><a name="p749713568820"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 503**

**表 33**  响应Body参数

<a name="table18959175516816"></a>
<table><thead align="left"><tr id="row1195975519815"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p10497956386"><a name="p10497956386"></a><a name="p10497956386"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p18497125619811"><a name="p18497125619811"></a><a name="p18497125619811"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p114976568813"><a name="p114976568813"></a><a name="p114976568813"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row59599552810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p194971156681"><a name="p194971156681"></a><a name="p194971156681"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p749755612810"><a name="p749755612810"></a><a name="p749755612810"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p204971456482"><a name="p204971456482"></a><a name="p204971456482"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 34**  Error

<a name="table169612551589"></a>
<table><thead align="left"><tr id="row109612557812"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p164975561986"><a name="p164975561986"></a><a name="p164975561986"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p949775620811"><a name="p949775620811"></a><a name="p949775620811"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p114973561887"><a name="p114973561887"></a><a name="p114973561887"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row119611455981"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1049895611815"><a name="p1049895611815"></a><a name="p1049895611815"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p54981056584"><a name="p54981056584"></a><a name="p54981056584"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p14498856784"><a name="p14498856784"></a><a name="p14498856784"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row16961755488"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p149814568813"><a name="p149814568813"></a><a name="p149814568813"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p549818567819"><a name="p549818567819"></a><a name="p549818567819"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p19498195611812"><a name="p19498195611812"></a><a name="p19498195611812"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 504**

**表 35**  响应Body参数

<a name="table109633557818"></a>
<table><thead align="left"><tr id="row1096410557814"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p194989561810"><a name="p194989561810"></a><a name="p194989561810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p149885612819"><a name="p149885612819"></a><a name="p149885612819"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1498105617815"><a name="p1498105617815"></a><a name="p1498105617815"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row189641755285"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p94983567813"><a name="p94983567813"></a><a name="p94983567813"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1849812561784"><a name="p1849812561784"></a><a name="p1849812561784"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p124986561988"><a name="p124986561988"></a><a name="p124986561988"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 36**  Error

<a name="table996610552817"></a>
<table><thead align="left"><tr id="row1196675519818"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1149810561483"><a name="p1149810561483"></a><a name="p1149810561483"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p749865615816"><a name="p749865615816"></a><a name="p749865615816"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p20498056683"><a name="p20498056683"></a><a name="p20498056683"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row89669551088"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p74982569817"><a name="p74982569817"></a><a name="p74982569817"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p13498155616813"><a name="p13498155616813"></a><a name="p13498155616813"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p2049865613817"><a name="p2049865613817"></a><a name="p2049865613817"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row196685511818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p34989561589"><a name="p34989561589"></a><a name="p34989561589"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1249810561284"><a name="p1249810561284"></a><a name="p1249810561284"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p11499105611818"><a name="p11499105611818"></a><a name="p11499105611818"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

## 请求示例<a name="section1949913564820"></a>

```
PUT https://{endpoint}/v1/{project_id}/vpc-endpoints/938c8167-631e-40a4-99f9-493753fbd16b/policy

{
  "policy_statement" : [ {
    "Action" : [ "obs:*:*" ],
    "Resource" : [ "obs:*:*:*:*/*", "obs:*:*:*:*" ],
    "Effect" : "Allow"
  } ]
}
```

## 响应示例<a name="section1949915561814"></a>

**状态码： 200**

服务器已成功处理了请求

```
{
  "id" : "938c8167-631e-40a4-99f9-493753fbd16b",
  "status" : "accepted",
  "tags" : [ ],
  "jobId" : "endpoint_add_938c8167-631e-40a4-99f9-493753fbd16b",
  "marker_id" : 302035929,
  "active_status" : [ "active" ],
  "vpc_id" : "0da03835-1dcf-4361-9b87-34139d58dd59",
  "service_type" : "gateway",
  "project_id" : "0605767a3300d5762fb7c0186d9e1779",
  "routetables" : [ "99477d3b-87f6-49d2-8f3b-2ffc72731a38" ],
  "created_at" : "2022-08-03T03:03:54Z",
  "updated_at" : "2022-08-03T03:03:57Z",
  "endpoint_service_id" : "4651bc78-5cec-41b7-b448-f77326ebbed0",
  "endpoint_service_name" : "br-iaas-odin1.obs_test.4651bc78-5cec-41b7-b448-f77326ebbed0",
  "policy_statement" : [ {
    "Action" : [ "obs:*:*" ],
    "Resource" : [ "obs:*:*:*:*/*", "obs:*:*:*:*" ],
    "Effect" : "Allow"
  } ],
  "specification_name" : "default",
  "enable_status" : "enable",
  "description" : "",
  "endpoint_pool_id" : "b0ad6a4f-55c0-43f1-a26d-278639661fc2"
}
```

## 状态码<a name="section16500756680"></a>

<a name="status_code"></a>
<table><thead align="left"><tr id="row1597610551984"><th class="cellrowborder" valign="top" width="15%" id="mcps1.1.3.1.1"><p id="p10500205614811"><a name="p10500205614811"></a><a name="p10500205614811"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="85%" id="mcps1.1.3.1.2"><p id="p1450018561882"><a name="p1450018561882"></a><a name="p1450018561882"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row29768551285"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p1350010566817"><a name="p1350010566817"></a><a name="p1350010566817"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p35001856588"><a name="p35001856588"></a><a name="p35001856588"></a>服务器已成功处理了请求</p>
</td>
</tr>
<tr id="row11976115519810"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p185001560814"><a name="p185001560814"></a><a name="p185001560814"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p25004561584"><a name="p25004561584"></a><a name="p25004561584"></a>服务器未能处理请求</p>
</td>
</tr>
<tr id="row597675512819"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p55001561785"><a name="p55001561785"></a><a name="p55001561785"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p155007563812"><a name="p155007563812"></a><a name="p155007563812"></a>被请求的页面需要用户名和密码</p>
</td>
</tr>
<tr id="row59760551981"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p195002561816"><a name="p195002561816"></a><a name="p195002561816"></a>403</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p115004561818"><a name="p115004561818"></a><a name="p115004561818"></a>对被请求页面的访问被禁止</p>
</td>
</tr>
<tr id="row17977135518812"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p205001056386"><a name="p205001056386"></a><a name="p205001056386"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p050113561818"><a name="p050113561818"></a><a name="p050113561818"></a>服务器无法找到被请求的页面</p>
</td>
</tr>
<tr id="row1397715551584"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p135011656188"><a name="p135011656188"></a><a name="p135011656188"></a>405</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p850116567818"><a name="p850116567818"></a><a name="p850116567818"></a>请求中指定的方法不被允许</p>
</td>
</tr>
<tr id="row2977255289"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p550195615819"><a name="p550195615819"></a><a name="p550195615819"></a>406</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p1950110566814"><a name="p1950110566814"></a><a name="p1950110566814"></a>服务器生成的响应无法被客户端所接受</p>
</td>
</tr>
<tr id="row10977155280"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p1250118561986"><a name="p1250118561986"></a><a name="p1250118561986"></a>407</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p350111561813"><a name="p350111561813"></a><a name="p350111561813"></a>用户必须首先使用代理服务器进行验证，这样请求才会被处理</p>
</td>
</tr>
<tr id="row1497712551816"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p75012056681"><a name="p75012056681"></a><a name="p75012056681"></a>408</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p750115618813"><a name="p750115618813"></a><a name="p750115618813"></a>请求超出了服务器的等待时间</p>
</td>
</tr>
<tr id="row0977125518816"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p13501145613820"><a name="p13501145613820"></a><a name="p13501145613820"></a>409</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p3501256883"><a name="p3501256883"></a><a name="p3501256883"></a>由于冲突，请求无法被完成</p>
</td>
</tr>
<tr id="row14977255787"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p65015562810"><a name="p65015562810"></a><a name="p65015562810"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p25013567818"><a name="p25013567818"></a><a name="p25013567818"></a>请求未完成。服务异常</p>
</td>
</tr>
<tr id="row199772551813"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p17501115615815"><a name="p17501115615815"></a><a name="p17501115615815"></a>501</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p10501256285"><a name="p10501256285"></a><a name="p10501256285"></a>请求未完成。服务器不支持所请求的功能</p>
</td>
</tr>
<tr id="row1497711551980"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p1050113561987"><a name="p1050113561987"></a><a name="p1050113561987"></a>502</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p2050112569815"><a name="p2050112569815"></a><a name="p2050112569815"></a>请求未完成。服务器从上游服务器收到一个无效的响应</p>
</td>
</tr>
<tr id="row189774551185"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p185015561388"><a name="p185015561388"></a><a name="p185015561388"></a>503</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p165019561686"><a name="p165019561686"></a><a name="p165019561686"></a>请求未完成。系统暂时异常</p>
</td>
</tr>
<tr id="row09774551689"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p65010561589"><a name="p65010561589"></a><a name="p65010561589"></a>504</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p1250110561582"><a name="p1250110561582"></a><a name="p1250110561582"></a>网关超时</p>
</td>
</tr>
</tbody>
</table>

## 错误码<a name="section55015563817"></a>

请参见[错误码](错误码.md)。

