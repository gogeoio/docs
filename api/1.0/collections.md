---
title: "Collections"
excerpt: ""
---
A collection in the **goGeo** platform is equivalent to a table in relational databases. Each collection is associated to a database and is a set of documents. Each collection may be public or private. In private ones, only the user who owns the collection has access to them. On the other hand, public collections, also named shared, may be accessed by any users.
Each collection has the attributes defined in Table 1. 

[block:parameters]
{
  "data": {
    "h-0": "Attribute",
    "h-1": "Type",
    "h-2": "Properties",
    "h-3": "Description",
    "0-0": "database_id",
    "1-0": "collection_name",
    "2-0": "description",
    "3-0": "id",
    "4-0": "origin",
    "5-0": "username",
    "6-0": "public",
    "0-3": "The identifier of the database containing the collection. To define the database associated to collection, you can use the database identifier or name",
    "1-3": "The collection name converted to lowercase. The collection name must start with a letter or number. It may also contain an underline, but not as the first character. Any other special characters are NOT ALLOWED. Just underline is acepted as word separator.\nMinimum length: 3 characters.\nSome valid names: collection_places, 4example, my_new_collection",
    "2-3": "Collection description",
    "3-3": "Collection identifier",
    "4-3": "Public collection identifier associated with this collection",
    "5-3": "Name of the user who created the collection",
    "6-3": "Defines if the collection will be public",
    "0-2": "required\nread-only",
    "1-2": "required\nread-only",
    "2-2": "optional",
    "3-2": "read-only",
    "4-2": "read-only",
    "5-2": "read-only",
    "6-2": "read-only",
    "0-1": "String",
    "1-1": "String",
    "2-1": "String",
    "3-1": "String",
    "4-1": "String",
    "5-1": "String",
    "6-1": "String"
  },
  "cols": 4,
  "rows": 7
}
[/block]

[block:html]
{
  "html": "<div class='footer_table'>\nTable 1 - Attributes of collection.\n</div>\n\n<style>\n  .footer_table {\n  \ttext-align: center;\n    max-width: 400px;\n    margin: 10px auto 0px;\n    color: #888;\n    font-size: 0.9em;\n    margin-top: -21px;\n  }\n</style>"
}
[/block]
---
[block:html]
{
  "html": "<div class='div-middle'> \n  <a href='#'>\n    Top page &spades; </div>\n  </a>\n</div>\n\n\n<div class='div-forward'> \n  <a href='/v1.0/docs/create-a-collection'>\n    Next &raquo; </div>\n  </a>\n</div>\n\n<style>\n  .div-middle {\n  \ttext-align: center;\n\t\tmargin-top: -15px;\n  }\n  \n  .div-forward {\n  \tfloat: right;\n    padding-right: 15px;\n\t\tmargin-top: -20px;\n  }\n</style>"
}
[/block]