PMS
===

A PHP CMS

This is gonna be a simple CMS, used to create simple webshops
for amateur/hobbyists that have a little too much junk in their backyard
and want to get rid of it for some money/trading.

DATABASE DESIGN:
  product table:
    INT     id
    VARCHAR name
    VARCHAR category
    VARCHAR short_descriptino
    TEXT    long_description
    ENUM    selltype ( 1 price, bidding, bidding from)
    INT     price
    INT     minimum_bidding_price
    
Features:
1 admin login system
viewing templates


File manager:
basicsettings.php
  Set the shop title, owner, and such
  
database.php
  database actions file
  
index.php
  index page
  
admin.php
  admin page
  
