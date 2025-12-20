[中文说明](README_CN.md)

# node-red-nodes

- Improved documentation for some Node-RED nodes.
- Enhanced some nodes to improve usability.


## Improvement List

###  odoo xmlrpc

- `search_read` and `search` nodes now support backend `limit`, `offset`, and `order` parameters.
- `search` node added a `Count` property to return the number of records.
- `config` node added a name field to intuitively view the account used in upper-level nodes, as account permissions vary and previously one had to click to know which account was used.
- Errors in each node can now be caught by the `catch` node.
- The color of each node has been changed to Odoo's color.


