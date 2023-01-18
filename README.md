SELECT NAME AS Customers FROM Customers 
WHERE ID NOT IN (SELECT customerId  FROM Orders );
