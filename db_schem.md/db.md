d_purchase
|属性名|型|PK|NN|FK|
|------|--|--|--|--|
|order_id|bigint(20)|〇|〇||<br>
|customer_code|varchar(50)||〇||<br>
|purchase_date|date||〇||<br>
|total_price|int(11)||〇||<br>

d_purchase_detail
|属性名|型|PK|NN|FK|
|------|--|--|--|--|
|detail_id|bigint(20)|〇|〇||
|order_id|bigint(20) |〇|〇||
|item_code|int(11)|〇|〇|〇|
|price|int(11) ||〇||
|num|int(11)||〇||

m_customers
|属性名|型|PK|NN|FK|
|------|--|--|--|--|
|customse_code|varchar(50)|〇|〇||
|pass|varchar(50)|〇|〇|〇|
|name|varchar(20)||〇||
|address|varchar(100)||〇||
|tel|varchar(20)||〇||
|mail|varchar(100)||〇||
|del_flag|int(11)||〇||
|reg_date|deta||〇||




m_category
|属性名|型|PK|NN|FK|
|------|--|--|--|--|
|category_id|int(11)|〇|〇||
|name|varchar(20)||〇||
|reg_data|||〇||

m_items
|属性名|型|PK|NN|FK|
|------|--|--|--|--|
|item_code|int(11)|〇|〇||
|item_name|varchar(50)||〇||
|price|int(11)||〇||
|categoey_id|int(11)||〇|〇|
|image|varchar(20)||〇||
|detail|varchar(500)||||
|del_flag|int(11)||||
|reg_date|date||〇||
