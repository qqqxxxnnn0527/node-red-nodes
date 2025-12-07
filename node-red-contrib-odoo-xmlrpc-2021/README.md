# node-red-contrib-odoo-xmlrpc-2021

## Additions in this fork

I picked up the work by https://github.com/crottolo/ and added a node to execute methods/buttons via calling the *execute_kw* function. This got necessary to fire actions in Odoo like confirming production orders etc.

## Example message properties

### search read

msg.filters = [["|",["phone","ilike", msg.payload],["mobile","=", msg.payload]]];  
msg.filters = [[["bom_id","=", msg.bom_id]]];  
msg.filters = [[["id","=", 23]]];

msg.offset = 0;  
msg.limit = 0;

msg.fields = (['name', 'fiscalcode']); 

### update

msg.payload = [[id1，id2，id3]， {"field_name1": "new value1"}]