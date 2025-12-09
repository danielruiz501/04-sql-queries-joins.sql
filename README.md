# MySQL queries joins

SELECT o.id, c.name, o.order_date
FROM orders o
JOIN customers c ON o.customer_id = c.id;
