# API概览<a name="vpcep_02_0000"></a>

VPC终端节点提供自研的REST接口。

通过使用VPC终端节点所提供的接口，您可以完整的使用VPC终端节点的所有功能。VPC终端节点主要包括终端节点和终端节点服务两种资源对象。

VPC终端节点提供的具体API如[表1](#zh-cn_topic_0178454981_zh-cn_topic_0173706804_table420812113211)所示。

**表 1**  接口说明

<a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_table420812113211"></a>
<table><thead align="left"><tr id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_row1527972153211"><th class="cellrowborder" valign="top" width="26.25%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p427918210322"><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p427918210322"></a><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p427918210322"></a>子类型</p>
</th>
<th class="cellrowborder" valign="top" width="73.75%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p12279121173212"><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p12279121173212"></a><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p12279121173212"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1940921382316"><td class="cellrowborder" valign="top" width="26.25%" headers="mcps1.2.3.1.1 "><p id="p7332214162313"><a name="p7332214162313"></a><a name="p7332214162313"></a>版本管理接口</p>
</td>
<td class="cellrowborder" valign="top" width="73.75%" headers="mcps1.2.3.1.2 "><p id="p14332191419235"><a name="p14332191419235"></a><a name="p14332191419235"></a>VPC终端节点API版本查询接口，支持查询所有API或者指定API的版本号。</p>
</td>
</tr>
<tr id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_row1227932183218"><td class="cellrowborder" valign="top" width="26.25%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p11201229163219"><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p11201229163219"></a><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p11201229163219"></a>终端节点服务接口</p>
</td>
<td class="cellrowborder" valign="top" width="73.75%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p1279521143211"><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p1279521143211"></a><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p1279521143211"></a>终端节点服务接口，支持创建、修改、查询、删除终端节点服务、查询列表、查询白名单规则、添加或删除白名单规则、查询连接的终端节点、接受或拒绝终端节点等。</p>
<p id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p11279162110325"><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p11279162110325"></a><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p11279162110325"></a>通过这些接口，您可以管理终端节点服务、根据自身业务状况设置规则，来向终端节点提供服务。</p>
</td>
</tr>
<tr id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_row227972163219"><td class="cellrowborder" valign="top" width="26.25%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p2686535123212"><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p2686535123212"></a><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p2686535123212"></a>终端节点接口</p>
</td>
<td class="cellrowborder" valign="top" width="73.75%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p103673385325"><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p103673385325"></a><a name="zh-cn_topic_0178454981_zh-cn_topic_0173706804_p103673385325"></a>终端节点接口，包括创建、查询、删除终端节点、查询列表，通过这些接口您可以管理终端节点来使用终端节点服务所提供的服务。</p>
</td>
</tr>
<tr id="zh-cn_topic_0178454981_row393263416215"><td class="cellrowborder" valign="top" width="26.25%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0178454981_p149326341827"><a name="zh-cn_topic_0178454981_p149326341827"></a><a name="zh-cn_topic_0178454981_p149326341827"></a>资源配额接口</p>
</td>
<td class="cellrowborder" valign="top" width="73.75%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0178454981_p293212340215"><a name="zh-cn_topic_0178454981_p293212340215"></a><a name="zh-cn_topic_0178454981_p293212340215"></a>VPC终端节点资源配额查询接口，支持查询VPC终端节点的终端节点服务和终端节点资源的配额。</p>
</td>
</tr>
<tr id="row12218551184513"><td class="cellrowborder" valign="top" width="26.25%" headers="mcps1.2.3.1.1 "><p id="p162190513457"><a name="p162190513457"></a><a name="p162190513457"></a>TAG接口</p>
</td>
<td class="cellrowborder" valign="top" width="73.75%" headers="mcps1.2.3.1.2 "><p id="p1721915124510"><a name="p1721915124510"></a><a name="p1721915124510"></a>VPC终端节点的标签管理接口，支持查询资源实例、批量添加或删除资源标签以及查询资源标签。</p>
</td>
</tr>
</tbody>
</table>

