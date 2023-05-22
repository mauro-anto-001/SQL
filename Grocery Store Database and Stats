CREATE TABLE boujees (id INTEGER PRIMARY KEY, item TEXT, price INTEGER, storage INTEGER, color TEXT); 
INSERT INTO boujees VALUES (1, "Shoes", 200.00, 50, "Green");
INSERT INTO boujees VALUES (2, "Shirts", 45.00, 50,"Green");
INSERT INTO boujees VALUES (3, "Shorts", 69.00,50, "Green");
INSERT INTO boujees VALUES (4, "Socks", 14.00,50,"Green" );
INSERT INTO boujees VALUES (5, "Jewlery", 500.00, 50,"Green");
INSERT INTO boujees VALUES (6, "Shoes", 200.00, 50,"Green");
INSERT INTO boujees VALUES (7, "Blankets", 500.00, 50,"Green");
INSERT INTO boujees VALUES (8, "Candy", 2.99, 50, "Brown");
INSERT INTO boujees VALUES (9, "Meat", 14.99, 50, "Red");
INSERT INTO boujees VALUES (10, "Bread", 5.99, 50, "Brown");
INSERT INTO boujees VALUES (11, "Pillow", 99.99, 50, "White");
INSERT INTO boujees VALUES (12, "Water Bottles", 49.99, 50, "Black");
INSERT INTO boujees VALUES (13, "Fans", 21.99, 50, "Black");
INSERT INTO boujees VALUES (14, "Computer", 2199.99, 50, "Silver");
INSERT INTO boujees VALUES (15, "iPhone", 1499.99, 50, "Gold");

--How does the price range for each item
SELECT item, price FROM boujees ORDER BY price desc;

--What is the most expensive item?
SELECT item, max(price) FROM boujees;

--How many item are colored gold?
SELECT count(color) FROM boujees WHERE color='Gold';
