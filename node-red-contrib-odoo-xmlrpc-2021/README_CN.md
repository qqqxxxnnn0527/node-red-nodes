# node-red-nodes

- 在使用一些Node-RED节点时完善一下帮助文档。
- 完善一些节点，提升易用性。


## 完善清单

###  odoo xmlrpc

- search_read、search节点支持后端limit、offset、order参数。
- search节点增加了Count属性，用于返回记录数。
- config节点增加名称字段，以便在上层节点直观查看所用账户，因为账户权限各不相同，之前都得点一下才能知道所用账户。
- 各节点报错时能够被catch节点抓住。
- 各节点的颜色改成了Odoo的颜色。