# 删除网关型终端节点policy<a name="DeleteEndpointPolicy"></a>

## 功能介绍<a name="section55116565818"></a>

功能介绍 删除网关型终端节点policy。

## 调试<a name="section185124561083"></a>

您可以在[API Explorer](https://apiexplorer.developer.huaweicloud.com/apiexplorer/doc?product=VPCEP&api=DeleteEndpointPolicy)中调试该接口，支持自动认证鉴权。API Explorer可以自动生成SDK代码示例，并提供SDK代码示例调试功能。

## URI<a name="section151210565817"></a>

DELETE /v1/\{project\_id\}/vpc-endpoints/\{vpc\_endpoint\_id\}/policy

**表 1**  路径参数

<a name="table651495615818"></a>
<table><thead align="left"><tr id="row851319561086"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.1"><p id="p15514145618810"><a name="p15514145618810"></a><a name="p15514145618810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="p1951495613817"><a name="p1951495613817"></a><a name="p1951495613817"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.3"><p id="p6515956480"><a name="p6515956480"></a><a name="p6515956480"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p551512568811"><a name="p551512568811"></a><a name="p551512568811"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1551317561186"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p12515105618812"><a name="p12515105618812"></a><a name="p12515105618812"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p5515205618817"><a name="p5515205618817"></a><a name="p5515205618817"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p551515561482"><a name="p551515561482"></a><a name="p551515561482"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p1151611561086"><a name="p1151611561086"></a><a name="p1151611561086"></a>项目ID</p>
<p id="p351612561180"><a name="p351612561180"></a><a name="p351612561180"></a>最小长度：<strong id="b05168569816"><a name="b05168569816"></a><a name="b05168569816"></a>1</strong></p>
<p id="p85166569810"><a name="p85166569810"></a><a name="p85166569810"></a>最大长度：<strong id="b3516185617812"><a name="b3516185617812"></a><a name="b3516185617812"></a>64</strong></p>
</td>
</tr>
<tr id="row15131756589"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p1451613565810"><a name="p1451613565810"></a><a name="p1451613565810"></a>vpc_endpoint_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p551635610819"><a name="p551635610819"></a><a name="p551635610819"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p1851717561681"><a name="p1851717561681"></a><a name="p1851717561681"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p851712561383"><a name="p851712561383"></a><a name="p851712561383"></a>终端节点的ID。</p>
<p id="p1517105618816"><a name="p1517105618816"></a><a name="p1517105618816"></a>最小长度：<strong id="b051795617818"><a name="b051795617818"></a><a name="b051795617818"></a>1</strong></p>
<p id="p451765618812"><a name="p451765618812"></a><a name="p451765618812"></a>最大长度：<strong id="b65174560818"><a name="b65174560818"></a><a name="b65174560818"></a>64</strong></p>
</td>
</tr>
</tbody>
</table>

## 请求参数<a name="section145178568811"></a>

**表 2**  请求Header参数

<a name="HeaderParameter"></a>
<table><thead align="left"><tr id="row1951820561281"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.1"><p id="p18519155613815"><a name="p18519155613815"></a><a name="p18519155613815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="p17519175610816"><a name="p17519175610816"></a><a name="p17519175610816"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.3"><p id="p115190561813"><a name="p115190561813"></a><a name="p115190561813"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p7519175618812"><a name="p7519175618812"></a><a name="p7519175618812"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row9518956489"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p8520756080"><a name="p8520756080"></a><a name="p8520756080"></a>X-Auth-Token</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p452012561589"><a name="p452012561589"></a><a name="p452012561589"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p6520956588"><a name="p6520956588"></a><a name="p6520956588"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p15520205618815"><a name="p15520205618815"></a><a name="p15520205618815"></a>用户Token。通过调用IAM服务获取用户Token接口获取(响应消息头中X-Subject-Token的值)。</p>
<p id="p175200561784"><a name="p175200561784"></a><a name="p175200561784"></a>最小长度：<strong id="b16520105614811"><a name="b16520105614811"></a><a name="b16520105614811"></a>1</strong></p>
<p id="p16520456580"><a name="p16520456580"></a><a name="p16520456580"></a>最大长度：<strong id="b2052113561687"><a name="b2052113561687"></a><a name="b2052113561687"></a>2048</strong></p>
</td>
</tr>
<tr id="row351812561889"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="p85219561389"><a name="p85219561389"></a><a name="p85219561389"></a>Content-Type</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="p115212563810"><a name="p115212563810"></a><a name="p115212563810"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p1152117561481"><a name="p1152117561481"></a><a name="p1152117561481"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p1352118566812"><a name="p1352118566812"></a><a name="p1352118566812"></a>发送的实体的MIME类型。推荐用户默认使用application/json， 如果API是对象、镜像上传等接口，媒体类型可按照流类型的不同进行确定。</p>
<p id="p25216565814"><a name="p25216565814"></a><a name="p25216565814"></a>最小长度：<strong id="b1252216561485"><a name="b1252216561485"></a><a name="b1252216561485"></a>1</strong></p>
<p id="p2522185614811"><a name="p2522185614811"></a><a name="p2522185614811"></a>最大长度：<strong id="b1852285619817"><a name="b1852285619817"></a><a name="b1852285619817"></a>64</strong></p>
</td>
</tr>
</tbody>
</table>

## 响应参数<a name="section45221056287"></a>

**状态码： 200**

**表 3**  响应Body参数

<a name="response_EndpointResp"></a>
<table><thead align="left"><tr id="row15238566819"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p452655617810"><a name="p452655617810"></a><a name="p452655617810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p14526125610819"><a name="p14526125610819"></a><a name="p14526125610819"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p185267561086"><a name="p185267561086"></a><a name="p185267561086"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row85231756089"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1652618561587"><a name="p1652618561587"></a><a name="p1652618561587"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1052785619810"><a name="p1052785619810"></a><a name="p1052785619810"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p14527185610820"><a name="p14527185610820"></a><a name="p14527185610820"></a>终端节点的ID，唯一标识。</p>
</td>
</tr>
<tr id="row5523185614813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p165277561783"><a name="p165277561783"></a><a name="p165277561783"></a>service_type</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p852755615812"><a name="p852755615812"></a><a name="p852755615812"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p9527556688"><a name="p9527556688"></a><a name="p9527556688"></a>终端节点连接的终端节点服务类型。 ● gataway：由运维人员配置。用户无需创建，可直接使用。 ● interface：包括运维人员配置的云服务和用户自己创建的私有服务。 其中，运维人员配置的云服务无需创建，用户可直接使用。 您可以通过查询公共终端节点服务列表， 查看由运维人员配置的所有用户可见且可连接的终端节点服务， 并通过创建终端节点服务创建Interface类型的终端节点服务。</p>
</td>
</tr>
<tr id="row1552312561087"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p175281356686"><a name="p175281356686"></a><a name="p175281356686"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1752814561788"><a name="p1752814561788"></a><a name="p1752814561788"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p10528175611817"><a name="p10528175611817"></a><a name="p10528175611817"></a>终端节点的连接状态。 ● pendingAcceptance：待接受 ● creating：创建中 ● accepted：已接受 ● failed：失败</p>
</td>
</tr>
<tr id="row25231556481"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p12528185612814"><a name="p12528185612814"></a><a name="p12528185612814"></a>active_status</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p25281756787"><a name="p25281756787"></a><a name="p25281756787"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p152920566816"><a name="p152920566816"></a><a name="p152920566816"></a>帐号状态。 ● frozen：冻结 ● active：解冻</p>
</td>
</tr>
<tr id="row1552312563813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p85294563810"><a name="p85294563810"></a><a name="p85294563810"></a>endpoint_service_name</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p15529115616813"><a name="p15529115616813"></a><a name="p15529115616813"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p195291256181"><a name="p195291256181"></a><a name="p195291256181"></a>终端节点服务的名称。</p>
</td>
</tr>
<tr id="row1752313564818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p5530656685"><a name="p5530656685"></a><a name="p5530656685"></a>marker_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p853019562820"><a name="p853019562820"></a><a name="p853019562820"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1553017563812"><a name="p1553017563812"></a><a name="p1553017563812"></a>终端节点的报文标识。</p>
</td>
</tr>
<tr id="row252395618810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1753016561785"><a name="p1753016561785"></a><a name="p1753016561785"></a>endpoint_service_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p653016569818"><a name="p653016569818"></a><a name="p653016569818"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p165311356581"><a name="p165311356581"></a><a name="p165311356581"></a>终端节点服务的ID。</p>
</td>
</tr>
<tr id="row0524256682"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1453114561689"><a name="p1453114561689"></a><a name="p1453114561689"></a>enable_dns</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p8531556781"><a name="p8531556781"></a><a name="p8531556781"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1531156280"><a name="p1531156280"></a><a name="p1531156280"></a>是否创建域名。 ● true：创建域名 ● false：不创建域名 说明 当创建连接gateway类型终端节点服务的终端节点时， “enable_dns”设置为true或者false，均不创建域名。</p>
</td>
</tr>
<tr id="row15241356787"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p115311456588"><a name="p115311456588"></a><a name="p115311456588"></a>dns_names</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p195328568818"><a name="p195328568818"></a><a name="p195328568818"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p155321356285"><a name="p155321356285"></a><a name="p155321356285"></a>访问所连接的终端节点服务的域名。 当“enable_dns”为true时，该参数可见。</p>
</td>
</tr>
<tr id="row65241556285"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p16532056486"><a name="p16532056486"></a><a name="p16532056486"></a>ip</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p9532155619815"><a name="p9532155619815"></a><a name="p9532155619815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p15329561481"><a name="p15329561481"></a><a name="p15329561481"></a>访问所连接的终端节点服务的IP。 仅当同时满足如下条件时，返回该参数： 当查询连接interface类型终端节点服务的终端节点时。 终端节点服务启用“连接审批”功能，且已经“接受”连接审批。 “status”可以是“accepted”或者“rejected（仅支持“接受”连接审批后再“拒绝”的情况）”。</p>
</td>
</tr>
<tr id="row1252413567811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p10533115619817"><a name="p10533115619817"></a><a name="p10533115619817"></a>vpc_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p15331567810"><a name="p15331567810"></a><a name="p15331567810"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p125331756183"><a name="p125331756183"></a><a name="p125331756183"></a>终端节点所在的VPC的ID。</p>
</td>
</tr>
<tr id="row115241756386"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p13534195619812"><a name="p13534195619812"></a><a name="p13534195619812"></a>subnet_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p165344561585"><a name="p165344561585"></a><a name="p165344561585"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p953419564813"><a name="p953419564813"></a><a name="p953419564813"></a>vpc_id对应VPC下已创建的网络（network）的ID，UUID格式。</p>
</td>
</tr>
<tr id="row1752412563816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p11534456389"><a name="p11534456389"></a><a name="p11534456389"></a>created_at</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p7534175619813"><a name="p7534175619813"></a><a name="p7534175619813"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p753519561818"><a name="p753519561818"></a><a name="p753519561818"></a>终端节点的创建时间。 采用UTC时间格式，格式为：YYYY-MM-DDTHH:MM:SSZ</p>
</td>
</tr>
<tr id="row1652415561682"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1753535617816"><a name="p1753535617816"></a><a name="p1753535617816"></a>updated_at</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p19535456988"><a name="p19535456988"></a><a name="p19535456988"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p353515620812"><a name="p353515620812"></a><a name="p353515620812"></a>终端节点的更新时间。 采用UTC时间格式，格式为：YYYY-MM-DDTHH:MM:SSZ</p>
</td>
</tr>
<tr id="row135241656281"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p18535155610814"><a name="p18535155610814"></a><a name="p18535155610814"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p17536185618817"><a name="p17536185618817"></a><a name="p17536185618817"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p65362056985"><a name="p65362056985"></a><a name="p65362056985"></a>项目ID，获取方法请参见获取项目ID。</p>
</td>
</tr>
<tr id="row1552416567815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p8536256484"><a name="p8536256484"></a><a name="p8536256484"></a>tags</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p35369561089"><a name="p35369561089"></a><a name="p35369561089"></a>Array of <a href="#response_TagList">TagList</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p05368561987"><a name="p05368561987"></a><a name="p05368561987"></a>标签列表，没有标签默认为空数组。</p>
</td>
</tr>
<tr id="row7524756483"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p105378563820"><a name="p105378563820"></a><a name="p105378563820"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p15537145614816"><a name="p15537145614816"></a><a name="p15537145614816"></a>Array of <a href="#response_QueryError">QueryError</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p15537056483"><a name="p15537056483"></a><a name="p15537056483"></a>错误信息。 当终端节点状态异常，即“status”的值为“failed”时，会返回该字段。</p>
</td>
</tr>
<tr id="row6524156480"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1353810562814"><a name="p1353810562814"></a><a name="p1353810562814"></a>whitelist</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p18538256688"><a name="p18538256688"></a><a name="p18538256688"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p175381756489"><a name="p175381756489"></a><a name="p175381756489"></a>控制访问终端节点的白名单。 若未创建，则返回空列表。 创建连接Interface类型终端节点服务的终端节点时，显示此参数。</p>
</td>
</tr>
<tr id="row165244562812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p3538456285"><a name="p3538456285"></a><a name="p3538456285"></a>enable_whitelist</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p653913564819"><a name="p653913564819"></a><a name="p653913564819"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1953920561816"><a name="p1953920561816"></a><a name="p1953920561816"></a>是否开启网络ACL隔离。 ● true：开启网络ACL隔离 ● false：不开启网络ACL隔离 若未指定，则返回false。 创建连接Interface类型终端节点服务的终端节点时，显示此参数。</p>
</td>
</tr>
<tr id="row7525956488"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p7539556583"><a name="p7539556583"></a><a name="p7539556583"></a>routetables</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p4539356085"><a name="p4539356085"></a><a name="p4539356085"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p185401561819"><a name="p185401561819"></a><a name="p185401561819"></a>路由表ID列表。 若未指定，返回默认VPC下路由表ID。 创建连接Gateway类型终端节点服务的终端节点时，显示此参数。</p>
</td>
</tr>
<tr id="row1552518563818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p45401756589"><a name="p45401756589"></a><a name="p45401756589"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p55401956886"><a name="p55401956886"></a><a name="p55401956886"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p954019561282"><a name="p954019561282"></a><a name="p954019561282"></a>描述字段，支持中英文字母、数字等字符，不支持“&lt;”或“&gt;”字符。</p>
</td>
</tr>
<tr id="row15251556088"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p135401569814"><a name="p135401569814"></a><a name="p135401569814"></a>policy_statement</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p35413560811"><a name="p35413560811"></a><a name="p35413560811"></a>Array of <a href="#response_PolicyStatement">PolicyStatement</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p554117569817"><a name="p554117569817"></a><a name="p554117569817"></a>只涉及开启双端固定的网关型终端节点，响应体展示此字段</p>
</td>
</tr>
<tr id="row65258568818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p16541256781"><a name="p16541256781"></a><a name="p16541256781"></a>endpoint_pool_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p6541125615811"><a name="p6541125615811"></a><a name="p6541125615811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1054216561887"><a name="p1054216561887"></a><a name="p1054216561887"></a>终端节点相关联的Pood的ID</p>
</td>
</tr>
<tr id="row155251656787"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p65421156985"><a name="p65421156985"></a><a name="p65421156985"></a>public_border_group</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p18542185619815"><a name="p18542185619815"></a><a name="p18542185619815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p654212561480"><a name="p654212561480"></a><a name="p654212561480"></a>终端节点关联的Public Border Group信息，只有当终端节点和边缘Pool相关联时才会返回改字段</p>
</td>
</tr>
</tbody>
</table>

**表 4**  TagList

<a name="response_TagList"></a>
<table><thead align="left"><tr id="row1054317561089"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p154495617816"><a name="p154495617816"></a><a name="p154495617816"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p554405620813"><a name="p554405620813"></a><a name="p554405620813"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p754455618814"><a name="p754455618814"></a><a name="p754455618814"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row205431561187"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1154417564815"><a name="p1154417564815"></a><a name="p1154417564815"></a>key</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p16545175616814"><a name="p16545175616814"></a><a name="p16545175616814"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p654513564817"><a name="p654513564817"></a><a name="p654513564817"></a>键。 最大长度36个unicode字符。 key不能为空。不能包含“=”、“*”、“&lt;”、“&gt;”、“\”、“,”、“|”和“/”，且首尾字符不能为空格。</p>
<p id="p1554595615817"><a name="p1554595615817"></a><a name="p1554595615817"></a>最小长度：<strong id="b205452569819"><a name="b205452569819"></a><a name="b205452569819"></a>1</strong></p>
<p id="p125451256285"><a name="p125451256285"></a><a name="p125451256285"></a>最大长度：<strong id="b75452560813"><a name="b75452560813"></a><a name="b75452560813"></a>36</strong></p>
</td>
</tr>
<tr id="row854316565814"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p654616568815"><a name="p654616568815"></a><a name="p654616568815"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p75461356787"><a name="p75461356787"></a><a name="p75461356787"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p8546756989"><a name="p8546756989"></a><a name="p8546756989"></a>值。 每个值最大长度43个unicode字符，可以为空字符串。 不能包含“=”、“*”、“&lt;”、“&gt;”、“\”、“,”、“|”和“/”，且首尾字符不能为空格。</p>
<p id="p1546756184"><a name="p1546756184"></a><a name="p1546756184"></a>最小长度：<strong id="b854713561589"><a name="b854713561589"></a><a name="b854713561589"></a>1</strong></p>
<p id="p155476561987"><a name="p155476561987"></a><a name="p155476561987"></a>最大长度：<strong id="b155472561088"><a name="b155472561088"></a><a name="b155472561088"></a>43</strong></p>
</td>
</tr>
</tbody>
</table>

**表 5**  QueryError

<a name="response_QueryError"></a>
<table><thead align="left"><tr id="row654713561884"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p185481356184"><a name="p185481356184"></a><a name="p185481356184"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p254865616814"><a name="p254865616814"></a><a name="p254865616814"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1554818561819"><a name="p1554818561819"></a><a name="p1554818561819"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row10547135613819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p25493561884"><a name="p25493561884"></a><a name="p25493561884"></a>error_code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p13549125610816"><a name="p13549125610816"></a><a name="p13549125610816"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p165492561289"><a name="p165492561289"></a><a name="p165492561289"></a>错误编码。</p>
</td>
</tr>
<tr id="row9547155616814"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1454910561812"><a name="p1454910561812"></a><a name="p1454910561812"></a>error_message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p8550756886"><a name="p8550756886"></a><a name="p8550756886"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p20550156686"><a name="p20550156686"></a><a name="p20550156686"></a>错误信息。</p>
</td>
</tr>
</tbody>
</table>

**表 6**  PolicyStatement

<a name="response_PolicyStatement"></a>
<table><thead align="left"><tr id="row185501356687"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p7551856285"><a name="p7551856285"></a><a name="p7551856285"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1155195620814"><a name="p1155195620814"></a><a name="p1155195620814"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p17552115619820"><a name="p17552115619820"></a><a name="p17552115619820"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1455035617817"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1255220562813"><a name="p1255220562813"></a><a name="p1255220562813"></a>Effect</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p95521556184"><a name="p95521556184"></a><a name="p95521556184"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p8552156888"><a name="p8552156888"></a><a name="p8552156888"></a>允许或拒绝，控制访问权限</p>
</td>
</tr>
<tr id="row1755015563818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p11552756286"><a name="p11552756286"></a><a name="p11552756286"></a>Action</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p955312561384"><a name="p955312561384"></a><a name="p955312561384"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p175536561181"><a name="p175536561181"></a><a name="p175536561181"></a>obs访问权限</p>
</td>
</tr>
<tr id="row1455118563812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p115531556789"><a name="p115531556789"></a><a name="p115531556789"></a>Resource</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1455310561685"><a name="p1455310561685"></a><a name="p1455310561685"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1555311567818"><a name="p1555311567818"></a><a name="p1555311567818"></a>obs对象</p>
</td>
</tr>
</tbody>
</table>

**状态码： 400**

**表 7**  响应Body参数

<a name="response_FailedRsp"></a>
<table><thead align="left"><tr id="row1554856183"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1455516561589"><a name="p1455516561589"></a><a name="p1455516561589"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p955515561486"><a name="p955515561486"></a><a name="p955515561486"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1955513568817"><a name="p1955513568817"></a><a name="p1955513568817"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row12554145615815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1055518561087"><a name="p1055518561087"></a><a name="p1055518561087"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1355520566819"><a name="p1355520566819"></a><a name="p1355520566819"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p055685613818"><a name="p055685613818"></a><a name="p055685613818"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 8**  Error

<a name="response_Error"></a>
<table><thead align="left"><tr id="row45569560811"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p055811565819"><a name="p055811565819"></a><a name="p055811565819"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1755817561284"><a name="p1755817561284"></a><a name="p1755817561284"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p185580560820"><a name="p185580560820"></a><a name="p185580560820"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row355765611819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p205591756989"><a name="p205591756989"></a><a name="p205591756989"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p9559175611811"><a name="p9559175611811"></a><a name="p9559175611811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p11559856882"><a name="p11559856882"></a><a name="p11559856882"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row1255755610818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p356065612818"><a name="p356065612818"></a><a name="p356065612818"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p356019561816"><a name="p356019561816"></a><a name="p356019561816"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1156016566814"><a name="p1156016566814"></a><a name="p1156016566814"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 401**

**表 9**  响应Body参数

<a name="table15619561786"></a>
<table><thead align="left"><tr id="row956115567810"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p956216561813"><a name="p956216561813"></a><a name="p956216561813"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p15621856881"><a name="p15621856881"></a><a name="p15621856881"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p16563156084"><a name="p16563156084"></a><a name="p16563156084"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row456115610819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p45631556889"><a name="p45631556889"></a><a name="p45631556889"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p55638561782"><a name="p55638561782"></a><a name="p55638561782"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p156310561385"><a name="p156310561385"></a><a name="p156310561385"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 10**  Error

<a name="table205649563816"></a>
<table><thead align="left"><tr id="row45649561280"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p556510561687"><a name="p556510561687"></a><a name="p556510561687"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p7565856683"><a name="p7565856683"></a><a name="p7565856683"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p35651556887"><a name="p35651556887"></a><a name="p35651556887"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row13564145612816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p15651256781"><a name="p15651256781"></a><a name="p15651256781"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p95661756489"><a name="p95661756489"></a><a name="p95661756489"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1456616561583"><a name="p1456616561583"></a><a name="p1456616561583"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row1656419561984"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p2918185616812"><a name="p2918185616812"></a><a name="p2918185616812"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p12918185610818"><a name="p12918185610818"></a><a name="p12918185610818"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p10919456981"><a name="p10919456981"></a><a name="p10919456981"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 403**

**表 11**  响应Body参数

<a name="table556713569816"></a>
<table><thead align="left"><tr id="row7567556389"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1991935611815"><a name="p1991935611815"></a><a name="p1991935611815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p891916561681"><a name="p891916561681"></a><a name="p891916561681"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p991911561787"><a name="p991911561787"></a><a name="p991911561787"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row145671356787"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p691935611817"><a name="p691935611817"></a><a name="p691935611817"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p14919125612815"><a name="p14919125612815"></a><a name="p14919125612815"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p2091915614813"><a name="p2091915614813"></a><a name="p2091915614813"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 12**  Error

<a name="table15691356785"></a>
<table><thead align="left"><tr id="row1569856689"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1092013567815"><a name="p1092013567815"></a><a name="p1092013567815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p129206561282"><a name="p129206561282"></a><a name="p129206561282"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p59201856689"><a name="p59201856689"></a><a name="p59201856689"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row757045618815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p69201656388"><a name="p69201656388"></a><a name="p69201656388"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1892012561389"><a name="p1892012561389"></a><a name="p1892012561389"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p592013561685"><a name="p592013561685"></a><a name="p592013561685"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row19570156886"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p169201856387"><a name="p169201856387"></a><a name="p169201856387"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p592045613819"><a name="p592045613819"></a><a name="p592045613819"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p492019562812"><a name="p492019562812"></a><a name="p492019562812"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 404**

**表 13**  响应Body参数

<a name="table14571256781"></a>
<table><thead align="left"><tr id="row1957220562815"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p392017567813"><a name="p392017567813"></a><a name="p392017567813"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p29200561784"><a name="p29200561784"></a><a name="p29200561784"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p9921556880"><a name="p9921556880"></a><a name="p9921556880"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row957215561083"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p59211756989"><a name="p59211756989"></a><a name="p59211756989"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1492116565814"><a name="p1492116565814"></a><a name="p1492116565814"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p11921135618817"><a name="p11921135618817"></a><a name="p11921135618817"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 14**  Error

<a name="table155731856387"></a>
<table><thead align="left"><tr id="row175741356983"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p109214565815"><a name="p109214565815"></a><a name="p109214565815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1292111567818"><a name="p1292111567818"></a><a name="p1292111567818"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p179211256382"><a name="p179211256382"></a><a name="p179211256382"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row55741564813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p392195616818"><a name="p392195616818"></a><a name="p392195616818"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p11921165618815"><a name="p11921165618815"></a><a name="p11921165618815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1492111561485"><a name="p1492111561485"></a><a name="p1492111561485"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row15574256784"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p692111561281"><a name="p692111561281"></a><a name="p692111561281"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p69215566811"><a name="p69215566811"></a><a name="p69215566811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p392115567816"><a name="p392115567816"></a><a name="p392115567816"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 405**

**表 15**  响应Body参数

<a name="table205761556289"></a>
<table><thead align="left"><tr id="row165775561981"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p792213561086"><a name="p792213561086"></a><a name="p792213561086"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p29220561817"><a name="p29220561817"></a><a name="p29220561817"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p492216561580"><a name="p492216561580"></a><a name="p492216561580"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1957795611816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1492219561187"><a name="p1492219561187"></a><a name="p1492219561187"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p169224562815"><a name="p169224562815"></a><a name="p169224562815"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p0922456183"><a name="p0922456183"></a><a name="p0922456183"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 16**  Error

<a name="table145798564810"></a>
<table><thead align="left"><tr id="row757910561985"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p17922105612820"><a name="p17922105612820"></a><a name="p17922105612820"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p139222056482"><a name="p139222056482"></a><a name="p139222056482"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p18922145618812"><a name="p18922145618812"></a><a name="p18922145618812"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row145794568813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p792214563810"><a name="p792214563810"></a><a name="p792214563810"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1692225612811"><a name="p1692225612811"></a><a name="p1692225612811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p149225565815"><a name="p149225565815"></a><a name="p149225565815"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row1858016561987"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p792215564818"><a name="p792215564818"></a><a name="p792215564818"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p169221556982"><a name="p169221556982"></a><a name="p169221556982"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p2922956989"><a name="p2922956989"></a><a name="p2922956989"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 406**

**表 17**  响应Body参数

<a name="table658215616814"></a>
<table><thead align="left"><tr id="row958218563815"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p17922205610814"><a name="p17922205610814"></a><a name="p17922205610814"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1792315617814"><a name="p1792315617814"></a><a name="p1792315617814"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p169236566812"><a name="p169236566812"></a><a name="p169236566812"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1458220568812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1692365619816"><a name="p1692365619816"></a><a name="p1692365619816"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1492365614816"><a name="p1492365614816"></a><a name="p1492365614816"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1592313569811"><a name="p1592313569811"></a><a name="p1592313569811"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 18**  Error

<a name="table1158415561383"></a>
<table><thead align="left"><tr id="row10584135618810"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p29235563817"><a name="p29235563817"></a><a name="p29235563817"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1392312561386"><a name="p1392312561386"></a><a name="p1392312561386"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p6923456385"><a name="p6923456385"></a><a name="p6923456385"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row13584185619813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p99231566815"><a name="p99231566815"></a><a name="p99231566815"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p129234562817"><a name="p129234562817"></a><a name="p129234562817"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1292315561812"><a name="p1292315561812"></a><a name="p1292315561812"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row958417565810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1892314562817"><a name="p1892314562817"></a><a name="p1892314562817"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p199231256187"><a name="p199231256187"></a><a name="p199231256187"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p179232564814"><a name="p179232564814"></a><a name="p179232564814"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 407**

**表 19**  响应Body参数

<a name="table258745611814"></a>
<table><thead align="left"><tr id="row1558719562813"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p16924195616818"><a name="p16924195616818"></a><a name="p16924195616818"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p292417561289"><a name="p292417561289"></a><a name="p292417561289"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1792410561481"><a name="p1792410561481"></a><a name="p1792410561481"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row858710564818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p9924356886"><a name="p9924356886"></a><a name="p9924356886"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1924185620819"><a name="p1924185620819"></a><a name="p1924185620819"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p49241569811"><a name="p49241569811"></a><a name="p49241569811"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 20**  Error

<a name="table145897561383"></a>
<table><thead align="left"><tr id="row135898568819"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p09248564811"><a name="p09248564811"></a><a name="p09248564811"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p19924456983"><a name="p19924456983"></a><a name="p19924456983"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p119241656382"><a name="p119241656382"></a><a name="p119241656382"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1158915561381"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1192495611814"><a name="p1192495611814"></a><a name="p1192495611814"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p14924195613815"><a name="p14924195613815"></a><a name="p14924195613815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p492465613813"><a name="p492465613813"></a><a name="p492465613813"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row35897561783"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p092485618820"><a name="p092485618820"></a><a name="p092485618820"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p189241561185"><a name="p189241561185"></a><a name="p189241561185"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p17924205616811"><a name="p17924205616811"></a><a name="p17924205616811"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 408**

**表 21**  响应Body参数

<a name="table55934566819"></a>
<table><thead align="left"><tr id="row16594105613811"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p129258561686"><a name="p129258561686"></a><a name="p129258561686"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1992515561818"><a name="p1992515561818"></a><a name="p1992515561818"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p15925256781"><a name="p15925256781"></a><a name="p15925256781"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row95947561819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p092511561983"><a name="p092511561983"></a><a name="p092511561983"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1092510561487"><a name="p1092510561487"></a><a name="p1092510561487"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p209251561782"><a name="p209251561782"></a><a name="p209251561782"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 22**  Error

<a name="table12595556083"></a>
<table><thead align="left"><tr id="row1459618561984"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p189251456783"><a name="p189251456783"></a><a name="p189251456783"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p199259561282"><a name="p199259561282"></a><a name="p199259561282"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p189259561985"><a name="p189259561985"></a><a name="p189259561985"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row459614566810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p8925356681"><a name="p8925356681"></a><a name="p8925356681"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p49251856688"><a name="p49251856688"></a><a name="p49251856688"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p189251756985"><a name="p189251756985"></a><a name="p189251756985"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row1459614567811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p13925956986"><a name="p13925956986"></a><a name="p13925956986"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p19925195614815"><a name="p19925195614815"></a><a name="p19925195614815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p392595615816"><a name="p392595615816"></a><a name="p392595615816"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 409**

**表 23**  响应Body参数

<a name="table05981256985"></a>
<table><thead align="left"><tr id="row859919565810"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p10926356683"><a name="p10926356683"></a><a name="p10926356683"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p149264563818"><a name="p149264563818"></a><a name="p149264563818"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p18926185610818"><a name="p18926185610818"></a><a name="p18926185610818"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1159914561081"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p189261561986"><a name="p189261561986"></a><a name="p189261561986"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1492615561681"><a name="p1492615561681"></a><a name="p1492615561681"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p99262561384"><a name="p99262561384"></a><a name="p99262561384"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 24**  Error

<a name="table16006561782"></a>
<table><thead align="left"><tr id="row1260119566811"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1292695619810"><a name="p1292695619810"></a><a name="p1292695619810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p109268561183"><a name="p109268561183"></a><a name="p109268561183"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p16927956781"><a name="p16927956781"></a><a name="p16927956781"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row960175616815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1592719566818"><a name="p1592719566818"></a><a name="p1592719566818"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p129277569811"><a name="p129277569811"></a><a name="p129277569811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p139275561819"><a name="p139275561819"></a><a name="p139275561819"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row1360165616810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p292714561684"><a name="p292714561684"></a><a name="p292714561684"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p092720562814"><a name="p092720562814"></a><a name="p092720562814"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p692712569818"><a name="p692712569818"></a><a name="p692712569818"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 500**

**表 25**  响应Body参数

<a name="table10603356880"></a>
<table><thead align="left"><tr id="row15604125619819"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p10927156586"><a name="p10927156586"></a><a name="p10927156586"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1992735614818"><a name="p1992735614818"></a><a name="p1992735614818"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p892735610819"><a name="p892735610819"></a><a name="p892735610819"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row86041156482"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p1927356383"><a name="p1927356383"></a><a name="p1927356383"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p99271856685"><a name="p99271856685"></a><a name="p99271856685"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p59271956488"><a name="p59271956488"></a><a name="p59271956488"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 26**  Error

<a name="table20606756689"></a>
<table><thead align="left"><tr id="row860715569816"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p10928155614818"><a name="p10928155614818"></a><a name="p10928155614818"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1592819562082"><a name="p1592819562082"></a><a name="p1592819562082"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1592812564811"><a name="p1592812564811"></a><a name="p1592812564811"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row26076561989"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p3928456487"><a name="p3928456487"></a><a name="p3928456487"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p09281556884"><a name="p09281556884"></a><a name="p09281556884"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p19928175611815"><a name="p19928175611815"></a><a name="p19928175611815"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row8607456889"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p12928205618814"><a name="p12928205618814"></a><a name="p12928205618814"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1892811561788"><a name="p1892811561788"></a><a name="p1892811561788"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p4928156783"><a name="p4928156783"></a><a name="p4928156783"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 501**

**表 27**  响应Body参数

<a name="table19609175614817"></a>
<table><thead align="left"><tr id="row86099561485"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p2928115615810"><a name="p2928115615810"></a><a name="p2928115615810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p5928756982"><a name="p5928756982"></a><a name="p5928756982"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1092812561986"><a name="p1092812561986"></a><a name="p1092812561986"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row3609165613818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p492811561487"><a name="p492811561487"></a><a name="p492811561487"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1692916561983"><a name="p1692916561983"></a><a name="p1692916561983"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p392965612816"><a name="p392965612816"></a><a name="p392965612816"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 28**  Error

<a name="table126110561818"></a>
<table><thead align="left"><tr id="row156117561812"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p119298562820"><a name="p119298562820"></a><a name="p119298562820"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p14929256988"><a name="p14929256988"></a><a name="p14929256988"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p49291156185"><a name="p49291156185"></a><a name="p49291156185"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row5611156484"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p2092975616815"><a name="p2092975616815"></a><a name="p2092975616815"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p892912565812"><a name="p892912565812"></a><a name="p892912565812"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p129290561284"><a name="p129290561284"></a><a name="p129290561284"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row861145614815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p792917569816"><a name="p792917569816"></a><a name="p792917569816"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p4929165619811"><a name="p4929165619811"></a><a name="p4929165619811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p892919562812"><a name="p892919562812"></a><a name="p892919562812"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 502**

**表 29**  响应Body参数

<a name="table261420565815"></a>
<table><thead align="left"><tr id="row161412561786"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p99309567819"><a name="p99309567819"></a><a name="p99309567819"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p0930256887"><a name="p0930256887"></a><a name="p0930256887"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p89301156786"><a name="p89301156786"></a><a name="p89301156786"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1361415563813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p093017561383"><a name="p093017561383"></a><a name="p093017561383"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p29306561785"><a name="p29306561785"></a><a name="p29306561785"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p15930756585"><a name="p15930756585"></a><a name="p15930756585"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 30**  Error

<a name="table4616125615814"></a>
<table><thead align="left"><tr id="row3616256787"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p129303561887"><a name="p129303561887"></a><a name="p129303561887"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1293019561188"><a name="p1293019561188"></a><a name="p1293019561188"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p093015569818"><a name="p093015569818"></a><a name="p093015569818"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1561635613812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p209304561286"><a name="p209304561286"></a><a name="p209304561286"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p1093045613813"><a name="p1093045613813"></a><a name="p1093045613813"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p149304566811"><a name="p149304566811"></a><a name="p149304566811"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row14616956885"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p39301561081"><a name="p39301561081"></a><a name="p39301561081"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p5930105617812"><a name="p5930105617812"></a><a name="p5930105617812"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1393017562080"><a name="p1393017562080"></a><a name="p1393017562080"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 503**

**表 31**  响应Body参数

<a name="table06191561584"></a>
<table><thead align="left"><tr id="row126191561085"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1293117565818"><a name="p1293117565818"></a><a name="p1293117565818"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p89319561383"><a name="p89319561383"></a><a name="p89319561383"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p1393112561681"><a name="p1393112561681"></a><a name="p1393112561681"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row96207561815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p693119561089"><a name="p693119561089"></a><a name="p693119561089"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p11931165612817"><a name="p11931165612817"></a><a name="p11931165612817"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p993175611816"><a name="p993175611816"></a><a name="p993175611816"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 32**  Error

<a name="table1862165620814"></a>
<table><thead align="left"><tr id="row862185616812"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p139311756588"><a name="p139311756588"></a><a name="p139311756588"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p15931105613819"><a name="p15931105613819"></a><a name="p15931105613819"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p99314563819"><a name="p99314563819"></a><a name="p99314563819"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row862155619816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p179311956187"><a name="p179311956187"></a><a name="p179311956187"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p993114561286"><a name="p993114561286"></a><a name="p993114561286"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1393117563819"><a name="p1393117563819"></a><a name="p1393117563819"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row116211856589"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p139319566817"><a name="p139319566817"></a><a name="p139319566817"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p39311156781"><a name="p39311156781"></a><a name="p39311156781"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p993110561788"><a name="p993110561788"></a><a name="p993110561788"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

**状态码： 504**

**表 33**  响应Body参数

<a name="table36241556783"></a>
<table><thead align="left"><tr id="row156242563814"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p1493285616814"><a name="p1493285616814"></a><a name="p1493285616814"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p1932175615814"><a name="p1932175615814"></a><a name="p1932175615814"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p693217560811"><a name="p693217560811"></a><a name="p693217560811"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row14624185614813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p39325568811"><a name="p39325568811"></a><a name="p39325568811"></a>error</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p3932556782"><a name="p3932556782"></a><a name="p3932556782"></a><a href="#response_Error">Error</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p59321856682"><a name="p59321856682"></a><a name="p59321856682"></a>提交任务异常时返回的异常信息</p>
</td>
</tr>
</tbody>
</table>

**表 34**  Error

<a name="table36261456188"></a>
<table><thead align="left"><tr id="row1862613561889"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="p179321356589"><a name="p179321356589"></a><a name="p179321356589"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p293216561889"><a name="p293216561889"></a><a name="p293216561889"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="p793218561282"><a name="p793218561282"></a><a name="p793218561282"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row2062619561816"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p109328564816"><a name="p109328564816"></a><a name="p109328564816"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p159326566815"><a name="p159326566815"></a><a name="p159326566815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p14932185615819"><a name="p14932185615819"></a><a name="p14932185615819"></a>任务异常错误信息描述</p>
</td>
</tr>
<tr id="row2626185613810"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="p3932195612816"><a name="p3932195612816"></a><a name="p3932195612816"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p11932356782"><a name="p11932356782"></a><a name="p11932356782"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="p1393255610818"><a name="p1393255610818"></a><a name="p1393255610818"></a>任务异常错误信息编码</p>
</td>
</tr>
</tbody>
</table>

## 请求示例<a name="section4932145610810"></a>

```
DELETE https://{endpoint}/v1/{project_id}/vpc-endpoints/938c8167-631e-40a4-99f9-493753fbd16b/policy
```

## 响应示例<a name="section1093312561582"></a>

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
  "specification_name" : "default",
  "enable_status" : "enable",
  "description" : "",
  "endpoint_pool_id" : "b0ad6a4f-55c0-43f1-a26d-278639661fc2"
}
```

## 状态码<a name="section9933856782"></a>

<a name="status_code"></a>
<table><thead align="left"><tr id="row263213561282"><th class="cellrowborder" valign="top" width="15%" id="mcps1.1.3.1.1"><p id="p89339561687"><a name="p89339561687"></a><a name="p89339561687"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="85%" id="mcps1.1.3.1.2"><p id="p79334568820"><a name="p79334568820"></a><a name="p79334568820"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row563217561086"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p129341256884"><a name="p129341256884"></a><a name="p129341256884"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p69345561685"><a name="p69345561685"></a><a name="p69345561685"></a>服务器已成功处理了请求</p>
</td>
</tr>
<tr id="row1663295616813"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p89345565819"><a name="p89345565819"></a><a name="p89345565819"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p9934205616818"><a name="p9934205616818"></a><a name="p9934205616818"></a>服务器未能处理请求</p>
</td>
</tr>
<tr id="row26321856487"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p99341569810"><a name="p99341569810"></a><a name="p99341569810"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p1793415610811"><a name="p1793415610811"></a><a name="p1793415610811"></a>被请求的页面需要用户名和密码</p>
</td>
</tr>
<tr id="row26327569813"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p79346561684"><a name="p79346561684"></a><a name="p79346561684"></a>403</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p149341856585"><a name="p149341856585"></a><a name="p149341856585"></a>对被请求页面的访问被禁止</p>
</td>
</tr>
<tr id="row13632956483"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p7934185612810"><a name="p7934185612810"></a><a name="p7934185612810"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p109349561280"><a name="p109349561280"></a><a name="p109349561280"></a>服务器无法找到被请求的页面</p>
</td>
</tr>
<tr id="row126320560818"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p149346561588"><a name="p149346561588"></a><a name="p149346561588"></a>405</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p149349561289"><a name="p149349561289"></a><a name="p149349561289"></a>请求中指定的方法不被允许</p>
</td>
</tr>
<tr id="row1563219561781"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p1593495618811"><a name="p1593495618811"></a><a name="p1593495618811"></a>406</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p1993414567816"><a name="p1993414567816"></a><a name="p1993414567816"></a>服务器生成的响应无法被客户端所接受</p>
</td>
</tr>
<tr id="row663219561086"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p169341156388"><a name="p169341156388"></a><a name="p169341156388"></a>407</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p179342562816"><a name="p179342562816"></a><a name="p179342562816"></a>用户必须首先使用代理服务器进行验证，这样请求才会被处理</p>
</td>
</tr>
<tr id="row46323562818"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p209345561886"><a name="p209345561886"></a><a name="p209345561886"></a>408</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p193420561282"><a name="p193420561282"></a><a name="p193420561282"></a>请求超出了服务器的等待时间</p>
</td>
</tr>
<tr id="row15633135619819"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p179341156080"><a name="p179341156080"></a><a name="p179341156080"></a>409</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p1193410561683"><a name="p1193410561683"></a><a name="p1193410561683"></a>由于冲突，请求无法被完成</p>
</td>
</tr>
<tr id="row5633256483"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p99340561188"><a name="p99340561188"></a><a name="p99340561188"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p12934115620812"><a name="p12934115620812"></a><a name="p12934115620812"></a>请求未完成。服务异常</p>
</td>
</tr>
<tr id="row563315568810"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p7934956587"><a name="p7934956587"></a><a name="p7934956587"></a>501</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p2934195611813"><a name="p2934195611813"></a><a name="p2934195611813"></a>请求未完成。服务器不支持所请求的功能</p>
</td>
</tr>
<tr id="row66333561381"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p139341156681"><a name="p139341156681"></a><a name="p139341156681"></a>502</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p79355561483"><a name="p79355561483"></a><a name="p79355561483"></a>请求未完成。服务器从上游服务器收到一个无效的响应</p>
</td>
</tr>
<tr id="row963313561884"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p8935135619814"><a name="p8935135619814"></a><a name="p8935135619814"></a>503</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p59351356187"><a name="p59351356187"></a><a name="p59351356187"></a>请求未完成。系统暂时异常</p>
</td>
</tr>
<tr id="row46333562817"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="p6935145616816"><a name="p6935145616816"></a><a name="p6935145616816"></a>504</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="p1893525616810"><a name="p1893525616810"></a><a name="p1893525616810"></a>网关超时</p>
</td>
</tr>
</tbody>
</table>

## 错误码<a name="section12935195610814"></a>

请参见[错误码](错误码.md)。

