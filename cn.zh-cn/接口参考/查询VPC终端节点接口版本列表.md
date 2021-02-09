# 查询VPC终端节点接口版本列表<a name="vpcep_06_0101"></a>

## 功能介绍<a name="section911804819271"></a>

查询VPC终端节点接口版本列表。

## URI<a name="section8252172943111"></a>

GET /

## 请求消息<a name="section4451152618322"></a>

-   请求样例

    GET https://\{endpoint\}/


## 响应消息<a name="section17102195273319"></a>

-   参数说明

    **表 1**  响应参数

    <a name="table173673267343"></a>
    <table><thead align="left"><tr id="row6419026173412"><th class="cellrowborder" valign="top" width="18.57%" id="mcps1.2.4.1.1"><p id="p6419426123416"><a name="p6419426123416"></a><a name="p6419426123416"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="26.939999999999998%" id="mcps1.2.4.1.2"><p id="p841911268345"><a name="p841911268345"></a><a name="p841911268345"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.49%" id="mcps1.2.4.1.3"><p id="p1241982643410"><a name="p1241982643410"></a><a name="p1241982643410"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1841962613418"><td class="cellrowborder" valign="top" width="18.57%" headers="mcps1.2.4.1.1 "><p id="p184199268345"><a name="p184199268345"></a><a name="p184199268345"></a>versions</p>
    </td>
    <td class="cellrowborder" valign="top" width="26.939999999999998%" headers="mcps1.2.4.1.2 "><p id="p4419426193412"><a name="p4419426193412"></a><a name="p4419426193412"></a>Array of objects</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.49%" headers="mcps1.2.4.1.3 "><p id="p1941992619345"><a name="p1941992619345"></a><a name="p1941992619345"></a>VPC终端节点接口版本信息列表，详细内容请参见<a href="#table13687304356">表2</a>。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 2**  VersionModel要素说明

    <a name="table13687304356"></a>
    <table><thead align="left"><tr id="row1148330133514"><th class="cellrowborder" valign="top" width="18.62%" id="mcps1.2.4.1.1"><p id="p12148163012355"><a name="p12148163012355"></a><a name="p12148163012355"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="27.12%" id="mcps1.2.4.1.2"><p id="p21481930173516"><a name="p21481930173516"></a><a name="p21481930173516"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.26%" id="mcps1.2.4.1.3"><p id="p191487308357"><a name="p191487308357"></a><a name="p191487308357"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row13148730103514"><td class="cellrowborder" valign="top" width="18.62%" headers="mcps1.2.4.1.1 "><p id="p414873012353"><a name="p414873012353"></a><a name="p414873012353"></a>status</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.12%" headers="mcps1.2.4.1.2 "><p id="p19148133018351"><a name="p19148133018351"></a><a name="p19148133018351"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.26%" headers="mcps1.2.4.1.3 "><p id="p15148130173519"><a name="p15148130173519"></a><a name="p15148130173519"></a>版本状态。</p>
    <a name="ul12195132314920"></a><a name="ul12195132314920"></a><ul id="ul12195132314920"><li>CURRENT：表示该版本为主推版本。</li><li>SUPPORT：表示为老版本，但是现在还在继续支持。</li><li>DEPRECATED：表示为废弃版本，存在后续删除的可能。</li></ul>
    </td>
    </tr>
    <tr id="row2148153033517"><td class="cellrowborder" valign="top" width="18.62%" headers="mcps1.2.4.1.1 "><p id="p814815307351"><a name="p814815307351"></a><a name="p814815307351"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.12%" headers="mcps1.2.4.1.2 "><p id="p181488307350"><a name="p181488307350"></a><a name="p181488307350"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.26%" headers="mcps1.2.4.1.3 "><p id="p214943013351"><a name="p214943013351"></a><a name="p214943013351"></a>版本ID。</p>
    </td>
    </tr>
    <tr id="row61491030163510"><td class="cellrowborder" valign="top" width="18.62%" headers="mcps1.2.4.1.1 "><p id="p0149143014358"><a name="p0149143014358"></a><a name="p0149143014358"></a>updated</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.12%" headers="mcps1.2.4.1.2 "><p id="p121491630183517"><a name="p121491630183517"></a><a name="p121491630183517"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.26%" headers="mcps1.2.4.1.3 "><p id="p4149830103515"><a name="p4149830103515"></a><a name="p4149830103515"></a>版本发布时间。</p>
    <p id="p871616113394"><a name="p871616113394"></a><a name="p871616113394"></a>采用UTC时间格式，格式为：YYYY-MM-DDTHH:MM:SSZ</p>
    </td>
    </tr>
    <tr id="row17149930163514"><td class="cellrowborder" valign="top" width="18.62%" headers="mcps1.2.4.1.1 "><p id="p514933013358"><a name="p514933013358"></a><a name="p514933013358"></a>version</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.12%" headers="mcps1.2.4.1.2 "><p id="p914923015352"><a name="p914923015352"></a><a name="p914923015352"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.26%" headers="mcps1.2.4.1.3 "><p id="p214923015359"><a name="p214923015359"></a><a name="p214923015359"></a>支持的版本号。</p>
    </td>
    </tr>
    <tr id="row138921150194"><td class="cellrowborder" valign="top" width="18.62%" headers="mcps1.2.4.1.1 "><p id="p837715239193"><a name="p837715239193"></a><a name="p837715239193"></a>min_version</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.12%" headers="mcps1.2.4.1.2 "><p id="p193771823181917"><a name="p193771823181917"></a><a name="p193771823181917"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.26%" headers="mcps1.2.4.1.3 "><p id="p378134613518"><a name="p378134613518"></a><a name="p378134613518"></a>支持的微版本号。若该版本API不支持微版本，则为空。</p>
    </td>
    </tr>
    <tr id="row101495301354"><td class="cellrowborder" valign="top" width="18.62%" headers="mcps1.2.4.1.1 "><p id="p18149173013518"><a name="p18149173013518"></a><a name="p18149173013518"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.12%" headers="mcps1.2.4.1.2 "><p id="p171493308352"><a name="p171493308352"></a><a name="p171493308352"></a>Array of objects</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.26%" headers="mcps1.2.4.1.3 "><p id="p6149113014357"><a name="p6149113014357"></a><a name="p6149113014357"></a>API的URL地址，详细内容请参见<a href="#table2072420713363">表3</a>。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 3**  VersionLink要素说明

    <a name="table2072420713363"></a>
    <table><thead align="left"><tr id="row1879514712367"><th class="cellrowborder" valign="top" width="18.67%" id="mcps1.2.4.1.1"><p id="p6795975366"><a name="p6795975366"></a><a name="p6795975366"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="27.04%" id="mcps1.2.4.1.2"><p id="p9795127193619"><a name="p9795127193619"></a><a name="p9795127193619"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.290000000000006%" id="mcps1.2.4.1.3"><p id="p147955719369"><a name="p147955719369"></a><a name="p147955719369"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row187958715368"><td class="cellrowborder" valign="top" width="18.67%" headers="mcps1.2.4.1.1 "><p id="p197951713612"><a name="p197951713612"></a><a name="p197951713612"></a>href</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.04%" headers="mcps1.2.4.1.2 "><p id="p197951874369"><a name="p197951874369"></a><a name="p197951874369"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.290000000000006%" headers="mcps1.2.4.1.3 "><p id="p779520783617"><a name="p779520783617"></a><a name="p779520783617"></a>当前API版本的引用地址。</p>
    </td>
    </tr>
    <tr id="row879514763612"><td class="cellrowborder" valign="top" width="18.67%" headers="mcps1.2.4.1.1 "><p id="p107951710363"><a name="p107951710363"></a><a name="p107951710363"></a>type</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.04%" headers="mcps1.2.4.1.2 "><p id="p10795472366"><a name="p10795472366"></a><a name="p10795472366"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.290000000000006%" headers="mcps1.2.4.1.3 "><p id="p5712332143113"><a name="p5712332143113"></a><a name="p5712332143113"></a>发送的实体的MIME类型，取值为application/json。</p>
    </td>
    </tr>
    <tr id="row079519743614"><td class="cellrowborder" valign="top" width="18.67%" headers="mcps1.2.4.1.1 "><p id="p117951723611"><a name="p117951723611"></a><a name="p117951723611"></a>rel</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.04%" headers="mcps1.2.4.1.2 "><p id="p979557123615"><a name="p979557123615"></a><a name="p979557123615"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.290000000000006%" headers="mcps1.2.4.1.3 "><p id="p1179513753617"><a name="p1179513753617"></a><a name="p1179513753617"></a>当前API版本和被引用地址的关系。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   响应样例

    ```
    {
      "versions":[
        {
          "updated":"2018-09-30T00:00:00Z",
          "version":"1",
          "min_version":"",
          "status":"CURRENT",
          "id":"v1",
          "links":[
            {
              "href":"https://{vpcep_uri}/v1",
              "type":"application/json",
              "rel":"self"
            }
          ]
        }
      ]
    }
    ```


## 状态码<a name="section88561438153717"></a>

状态码请参见[状态码](状态码.md)。

