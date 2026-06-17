# select-limit-e-AVG
HT-SIS-01-M-26-10495
SELECT TOP FROM WHERE ORDER BY
-- 1
SELECT * FROM OrderDetails
LIMIT 5;

-- 2
SELECT * FROM OrderDetails
WHERE Quantity > 10
ORDER BY OrderID
LIMIT 3;

-- 3
SELECT * FROM OrderDetails
ORDER BY Quantity DESC
LIMIT 7;

-- 4
SELECT * FROM OrderDetails
WHERE ProductID = 4
LIMIT 10;

-- 5
SELECT * FROM OrderDetails
ORDER BY OrderDetailID ASC
LIMIT 2;

-- 6
SELECT * FROM OrderDetails
ORDER BY Quantity DESC
LIMIT 15;

-- 7
SELECT * FROM OrderDetails
ORDER BY Quantity ASC, ProductID
LIMIT 20;

-- 8
SELECT * FROM OrderDetails
ORDER BY Quantity DESC, OrderDetailID
LIMIT 8;

-- 9
SELECT * FROM OrderDetails
WHERE ProductID > 3
ORDER BY OrderID
LIMIT 5;

-- 10
SELECT * FROM OrderDetails
ORDER BY OrderID DESC, Quantity
LIMIT 10;

-- 11
SELECT * FROM OrderDetails
WHERE Quantity < 15
ORDER BY OrderDetailID
LIMIT 12;

-- 12
SELECT * FROM OrderDetails
WHERE MOD(ProductID,2) = 0
ORDER BY Quantity
LIMIT 6;

-- 13
SELECT * FROM OrderDetails
ORDER BY ProductID DESC
LIMIT 5;

-- 14
SELECT * FROM OrderDetails
ORDER BY OrderID, Quantity
LIMIT 7;

-- 15
SELECT * FROM OrderDetails
WHERE Quantity < 8
ORDER BY OrderID, ProductID
LIMIT 3;

-- 16
SELECT * FROM OrderDetails
ORDER BY Quantity DESC, OrderID
LIMIT 9;

-- 17
SELECT * FROM OrderDetails
WHERE OrderID = 20
LIMIT 2;

-- 18
SELECT * FROM OrderDetails
WHERE Quantity > 25
ORDER BY ProductID
LIMIT 10;

-- 19
SELECT * FROM OrderDetails
WHERE OrderDetailID < 50
ORDER BY Quantity
LIMIT 4;

-- 20
SELECT * FROM OrderDetails
WHERE OrderID BETWEEN 10 AND 30
ORDER BY ProductID
LIMIT 6;

-- 21
SELECT * FROM OrderDetails
ORDER BY Quantity DESC, OrderDetailID
LIMIT 8;

-- 22
SELECT * FROM OrderDetails
WHERE ProductID LIKE '%7'
ORDER BY OrderID
LIMIT 5;

-- 23
SELECT * FROM OrderDetails
WHERE OrderID > 100
ORDER BY Quantity
LIMIT 3;

-- 24
SELECT * FROM OrderDetails
WHERE Quantity > 15
ORDER BY OrderDetailID
LIMIT 10;

-- 25
SELECT * FROM OrderDetails
ORDER BY OrderID ASC, ProductID
LIMIT 12;

-- 26
SELECT * FROM OrderDetails
WHERE MOD(ProductID,3) = 0
ORDER BY Quantity
LIMIT 7;

-- 27
SELECT * FROM OrderDetails
WHERE OrderDetailID BETWEEN 5 AND 50
ORDER BY OrderID
LIMIT 10;

-- 28
SELECT * FROM OrderDetails
ORDER BY Quantity DESC, ProductID
LIMIT 6;

-- 29
SELECT * FROM OrderDetails
WHERE MOD(ProductID,2) <> 0
ORDER BY Quantity
LIMIT 4;

-- 30
SELECT * FROM OrderDetails
WHERE OrderID > 15
ORDER BY ProductID
LIMIT 8;

-- 31
SELECT * FROM OrderDetails
WHERE Quantity < 5
ORDER BY OrderID
LIMIT 3;

-- 32
SELECT * FROM OrderDetails
WHERE MOD(ProductID,2) = 0
ORDER BY OrderID
LIMIT 5;

-- 33
SELECT * FROM OrderDetails
ORDER BY OrderDetailID DESC
LIMIT 10;

-- 34
SELECT * FROM OrderDetails
WHERE MOD(Quantity,5) = 0
ORDER BY ProductID
LIMIT 7;

-- 35
SELECT * FROM OrderDetails
ORDER BY ProductID ASC, OrderID
LIMIT 2;

-- 36
SELECT * FROM OrderDetails
WHERE OrderID LIKE '%1'
ORDER BY Quantity
LIMIT 8;

-- 37
SELECT * FROM OrderDetails
ORDER BY OrderID DESC, OrderDetailID
LIMIT 4;

-- 38
SELECT * FROM OrderDetails
WHERE Quantity > 30
ORDER BY ProductID
LIMIT 9;

-- 39
SELECT * FROM OrderDetails
ORDER BY ProductID ASC, OrderID
LIMIT 5;

-- 40
SELECT * FROM OrderDetails
ORDER BY OrderDetailID DESC, Quantity
LIMIT 6;

-- 41
SELECT * FROM OrderDetails
WHERE MOD(OrderID,2) <> 0
ORDER BY Quantity
LIMIT 10;

-- 42
SELECT * FROM OrderDetails
WHERE Quantity = 20
ORDER BY ProductID
LIMIT 3;

-- 43
SELECT * FROM OrderDetails
WHERE OrderDetailID < 200
ORDER BY OrderID
LIMIT 7;

-- 44
SELECT * FROM OrderDetails
WHERE OrderID BETWEEN 100 AND 200
ORDER BY ProductID
LIMIT 5;

-- 45
SELECT * FROM OrderDetails
ORDER BY Quantity DESC, OrderDetailID
LIMIT 12;

-- 46
SELECT * FROM OrderDetails
WHERE ProductID < 10
ORDER BY OrderID
LIMIT 9;

-- 47
SELECT * FROM OrderDetails
WHERE OrderID LIKE '%0'
ORDER BY Quantity
LIMIT 2;

-- 48
SELECT * FROM OrderDetails
ORDER BY OrderID ASC, ProductID
LIMIT 5;

-- 49
SELECT * FROM OrderDetails
WHERE MOD(Quantity,4) = 0
ORDER BY ProductID
LIMIT 6;

-- 50
SELECT * FROM OrderDetails
ORDER BY ProductID DESC, Quantity
LIMIT 10;

SELECT AVG FROM WHERE ORDER BY
-- 1
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails;

-- 2
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID > 10;

-- 3
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID = 5;

-- 4
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID < 50;

-- 5
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID > 100;

-- 6
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(ProductID,2) = 0;

-- 7
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(OrderDetailID,2) <> 0;

-- 8
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID BETWEEN 5 AND 15;

-- 9
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID LIKE '%0';

-- 10
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID BETWEEN 10 AND 30;

-- 11
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity > 25;

-- 12
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity < 10;

-- 13
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID > 7;

-- 14
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID < 20;

-- 15
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(Quantity,5) = 0;

-- 16
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID < 12;

-- 17
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID BETWEEN 15 AND 30;

-- 18
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID LIKE '2%';

-- 19
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID > 10;

-- 20
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(OrderID,2) <> 0;

-- 21
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(ProductID,3) = 0;

-- 22
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID > 30;

-- 23
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity BETWEEN 10 AND 20;

-- 24
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID LIKE '%5';

-- 25
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID IN (3,5,7);

-- 26
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity NOT BETWEEN 15 AND 25;

-- 27
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID BETWEEN 5 AND 15;

-- 28
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID = 100;

-- 29
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID BETWEEN 100 AND 200;

-- 30
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity > 20;

-- 31
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID NOT IN (1,2,3);

-- 32
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID LIKE '%2';

-- 33
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(Quantity,2) = 0;

-- 34
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID > 200;

-- 35
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID = 10;

-- 36
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID BETWEEN 50 AND 100;

-- 37
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID LIKE '1%';

-- 38
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(ProductID,5) = 0;

-- 39
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity NOT IN (5,10,15);

-- 40
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID < 10;

-- 41
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID > 20;

-- 42
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity = 15;

-- 43
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID IN (10,20,30);

-- 44
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE Quantity BETWEEN 5 AND 10;

-- 45
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID NOT LIKE '%3';

-- 46
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID > 30;

-- 47
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderID < 100;

-- 48
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE ProductID BETWEEN 10 AND 50;

-- 49
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE MOD(Quantity,4) = 0;

-- 50
SELECT AVG(Quantity) AS Media_Quantity
FROM OrderDetails
WHERE OrderDetailID LIKE '%0';
