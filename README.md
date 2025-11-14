# Currently working on this as a Full-stack Project
## Frontend Mentor - Product list with cart

![Design preview for the Product list with cart coding challenge](./preview.jpg)
[Frontend Mentor Project Link](https://www.frontendmentor.io/challenges/product-list-with-cart-5MmqLVAp_d)

### Working with HTML, CSS, JS, Laravel & MySQL

**Starting with ER Diagram & Connecting FK**

**Main Entities**
- Product
- Order
- User
- Product Category

**Attributes per Entity**
PRODUCT
- id
- name
- description
- price
- image_url
- stock
- discount
- category_id

ORDER
- id
- number/code
- tracking_number
- total_price
- promotional_code
- status
- user_id

USER
- id
- name
- email
- password

ORDER_PRODUCT
- id
- order_id
- product_id
- quantity (number of products in order)
- price_per_unit

USER_PRODUCT
- id
- product_id
- user_id

CATEGORY
- id
- name
- description