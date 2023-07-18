{% docs customers %}

### customers

This table contains customer and aggregated order data for customers

- Final table `jaffle_shop.customers`
- One record per customer
- Represents relationship between customers and orders
- Customer data can exist without orders, first_order_date is NULL when there are no orders
- Final table built using stg_customers and stg_orders

{% enddocs %}