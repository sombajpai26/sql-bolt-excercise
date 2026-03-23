EXCERCISE 11

1. Find the number of Artists in the studio
SELECT COUNT(*) AS Artist_Count
FROM Employees
WHERE Role = 'Artist';

2. Find the number of employees of each role
SELECT Role, COUNT(*) AS Count
FROM Employees
GROUP BY Role;

3. Find the total number of years employed by all Engineers
SELECT SUM(Years_Employed) AS Total_Years
FROM Employees
WHERE Role = 'Engineer';

EXCERCISE 12
1. Find the number of movies each director has directed
SELECT Director, COUNT(*) AS Movie_Count
FROM Movies
GROUP BY Director;

2. Find total domestic and international sales for each director
SELECT Director,
       SUM(Domestic_Sales) AS Total_Domestic_Sales,
       SUM(International_Sales) AS Total_International_Sales
FROM Movies
GROUP BY Director;
