CREATE TABLE inventory (id INTEGER PRIMARY KEY,item TEXT, cost INTEGER, sale_price INTEGER, quantity INTEGER); 

INSERT INTO inventory VALUES (1, "mens_tshirt_small", 5, 15, 10);
INSERT INTO inventory VALUES (2, "womens_tshirt_small", 5, 15, 9);
INSERT INTO inventory VALUES (3, "mens_tshirt_medium", 5, 15, 12);
INSERT INTO inventory VALUES (4, "womens_tshirt_medium", 5, 15, 15);
INSERT INTO inventory VALUES (5, "mens_tshirt_large", 5, 15, 15);
INSERT INTO inventory VALUES (6, "womens_tshirt_large", 5, 15, 13);
INSERT INTO inventory VALUES (7, "mens_tshirt_xlarge", 5, 15, 10);
INSERT INTO inventory VALUES (8, "womens_tshirt_xlarge", 5, 15, 11);
INSERT INTO inventory VALUES (9, "kids_tshirt_small", 4, 12, 8);
INSERT INTO inventory VALUES (10,"kids_tshirt_medium", 4, 12, 6);
INSERT INTO inventory VALUES (11, "kids_tshirt_large", 4, 12, 7);
INSERT INTO inventory VALUES (12, "kids_tshirt_xlarge", 4, 12, 3);
INSERT INTO inventory VALUES (13, "adult_sweatshirt_medium", 15, 45, 4);
INSERT INTO inventory VALUES (14, "adult_sweatshirt_large", 15, 45, 5);
INSERT INTO inventory VALUES (15, "adult_sweatshirt_xlarge", 15, 45, 7); 

SELECT * FROM inventory;
SELECT SUM(quantity) FROM inventory;

