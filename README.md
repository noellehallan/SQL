# SQL

CREATE TABLE toy_store (id INTEGER PRIMARY KEY, name TEXT, quantity INTEGER, age INTEGER, price INTEGER);

INSERT INTO toy_store VALUES (1, "Book", 45, 2, 5);
INSERT INTO toy_store VALUES (2, "Car", 30, 3, 5);
INSERT INTO toy_store VALUES (3, "Truck", 18, 3, 8);
INSERT INTO toy_store VALUES (4, "Doll", 10, 2, 15);
INSERT INTO toy_store VALUES (5, "Doll Clothes", 20, 2, 10);
INSERT INTO toy_store VALUES (6, "Puzzle", 15, 3, 7);
INSERT INTO toy_store VALUES (7, "Bubble Blower", 8, 2, 6);
INSERT INTO toy_store VALUES (8, "Playdoh", 25, 2, 1);
INSERT INTO toy_store VALUES (9, "Train", 12, 3, 8);
INSERT INTO toy_store VALUES (10, "Train Track", 5, 3, 20);
INSERT INTO toy_store VALUES (11, "Doll Stroller", 5, 2, 18);
INSERT INTO toy_store VALUES (12, "Ball", 14, 1, 4);
INSERT INTO toy_store VALUES (13, "Bubbles", 22, 2, 1);
INSERT INTO toy_store VALUES (14, "Stuffed Animal", 16, 1, 12);
INSERT INTO toy_store VALUES (15, "Block Set", 8, 2, 22);

SELECT * FROM toy_store;
SELECT * FROM toy_store ORDER BY price;

SELECT SUM(quantity) FROM toy_store;
SELECT MAX(age) FROM toy_store;
SELECT MIN(age) FROM toy_store;
SELECT MAX(price) FROM toy_store;
SELECT MIN(price) FROM toy_store;

