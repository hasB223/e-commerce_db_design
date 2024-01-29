## E-Commerce Database Design
- A theoretical design for an e-commerce platform's database
- Also included the create table prompt for MySQL

Tools used:
- MySQL
- Lucidchart

Assumptions:
- One user may have multiple address
- One user may own many shop
- One shop can have multiple owner
- Same item would have different product_id if sold in different shop. This is because PRODUCTREVIEWS by the user consider the services (e.g. product's condition, packaging method, shipment time, free gifts, etc.) done by a particular shop. Therefore SHOPS and PRODUCTS has one-to-many relationship instead of many-to-many relationship