# SQL-Hackerrank


I'll use MySQL to solve the challenges.

Notes:

1. () is important in nested query
2. we can perform multiple operation after select [SELECT op1, op2.. from-----]
3. MINUS(on table) and -(arithmetic) are different
4. LENGTH() to find length 
5. LIMIT N to retrive first n row (syntax differs in other lang)
6. Every derived table must have its own alias
7. use REGEXP instead of LIKE for regex search | see other REGEXP_sdfdf | see mysql regex from GeeksForGeeks
8. UPPER or LOWER to convert string case..
9. SUBSTR or SUBSTRING (string, startindex[1 based](if negative start from last n character), length) to find substring
10. IN to check if some value exists in array.column or not
11. LEFT or RIGHT (string, length) finds substring from left.right of string
12. can not mix agreegate and non-agreegate in SELECT
13. cant use alias in count. use * instead
14. better use 'tablename.column_name' in join
15. Don't forget to use GROUP BY while using aggregate function











SELECT MIN MAX COUNT AVG SUM AS CONCAT() INTO IN IFNULLFROM AS  *USE ALIAS FOR SELF JOIN
INNER LEFT RIGHT FULL JOIN ON 
WHERE  BETWEEN AND OR NOT LIKE IN =>< IS NULL EXISTS ANY ALL SOME
GROUP BY
HAVING
ORDER BY ASC DESC
LIMIT

INSERT INTO VALUES

UPDATE SET WHERE

DELETE FROM WHERE
SELECT TOP/SELECT TOP X%

SELECT UNION UNION ALL SELECT

CASE  WHEN  THEN ELSE END AS

CREATE PROCEDURE AS GO    EXEC

DATEDIFF(maxdate,mindate) -> diff in days
CURRENT_DATE()

-- /**/

CREATE DROP DATABASE

BACKUP DATABASE TO DISK WITH DIFFERENTIAL

CREATE DROP TABLE

ALTER TABLE ADD DROP COLUMN ALTER COLUMN

constraints: NOT NULL, UNIQUW, PRIMARY KEY, FOREIGN KEY, CHECK, DEFAULT, INDEX CHECK DEFAULT AUTO_INCREMENT

CREATE TABLE CONSTRAINT  PRIMARY KEY 

ALTER TABLE ADD CONSTRAINT PRIMARY KEY

ALTER TABLE DROP PRIMARY KEY

CREATE TABLE FOREIGN KEY REFERENCES

ALTER TABLE MODIFY NOT NULLE

ALER TABLE ADD UNIQUE

ALTER TABLE ADD CONSTRAINT UNIQUE

CREATE  UNIQUE INDEX ON

CREATE VIEW AS

DROP
