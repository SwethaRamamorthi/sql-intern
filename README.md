EXAMPLE SCHEMA:

✅ 1. CUSTOMER Table Example
INSERT INTO Customer (customer_id, name, email, phone, address)
VALUES (1, 'Arjun Kumar', 'arjun.k@example.com', '9876543210', '123, MG Road, Chennai');
✅ 2. CATEGORY Table Example
INSERT INTO Category (category_id, category_name)
VALUES (1, 'Electronics');
✅ 3. PRODUCT Table Example
INSERT INTO Product (product_id, name, description, price, category_id)
VALUES (101, 'Bluetooth Headphones', 'Noise-canceling over-ear headphones', 2999.99, 1);
✅ 4. ORDERS Table Example
INSERT INTO Orders (order_id, customer_id, order_date, total_amount)
VALUES (5001, 1, '2025-06-23', 2999.99);
✅ 5. ORDERITEM Table Example
INSERT INTO OrderItem (order_item_id, order_id, product_id, quantity, price)
VALUES (9001, 5001, 101, 1, 2999.99);
✅ 6. PAYMENT Table Example
INSERT INTO Payment (payment_id, order_id, payment_date, amount, payment_method)
VALUES (7001, 5001, '2025-06-23', 2999.99, 'UPI');
✅ 7. SHIPMENT Table Example
INSERT INTO Shipment (shipment_id, order_id, shipment_date, delivery_date, status)
VALUES (8001, 5001, '2025-06-24', '2025-06-26', 'In Transit');
