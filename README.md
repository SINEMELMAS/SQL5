# SQL5
SELECT * FROM ARABALAR WHERE MARKA LIKE 'M%' 
SELECT * FROM ARABALAR WHERE ID BETWEEN 1 AND 100 
ORDER BY FIYAT
SELECT MIN(FIYAT),MAX(MOTOR),COUNT(*) FROM ARABALAR
SELECT MARKA FROM ARABALAR GROUP BY MARKA
SELECT YAKIT FROM ARABALAR GROUP BY YAKIT
SELECT MARKA , 
MIN(FIYAT) AS MINFIYAT, MAX(FIYAT) AS MAXFIYAT, AVG(FIYAT) AS AVGFIYAT
FROM ARABALAR
GROUP BY MARKA 
ORDER BY MARKA ASC
SELECT TOP 10 MARKA, MAX(FIYAT)  FROM ARABALAR 
GROUP BY MARKA ORDER BY MAX(FIYAT) DESC
