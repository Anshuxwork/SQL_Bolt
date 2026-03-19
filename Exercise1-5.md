# Exercise 1 — Tasks

# Movies Table

| id | title               | director          | year | length_minutes |
|----|--------------------|------------------|------|---------------|
| 1  | Toy Story          | John Lasseter    | 1995 | 81            |
| 2  | A Bug's Life       | John Lasseter    | 1998 | 95            |
| 3  | Toy Story 2        | John Lasseter    | 1999 | 93            |
| 4  | Monsters, Inc.     | Pete Docter      | 2001 | 92            |
| 5  | Finding Nemo       | Andrew Stanton   | 2003 | 107           |
| 6  | The Incredibles    | Brad Bird        | 2004 | 116           |
| 7  | Cars               | John Lasseter    | 2006 | 117           |
| 8  | Ratatouille        | Brad Bird        | 2007 | 115           |
| 9  | WALL-E             | Andrew Stanton   | 2008 | 104           |
| 10 | Up                 | Pete Docter      | 2009 | 101           |
| 11 | Toy Story 3        | Lee Unkrich      | 2010 | 103           |
| 12 | Cars 2             | John Lasseter    | 2011 | 120           |
| 13 | Brave              | Brenda Chapman   | 2012 | 102           |
| 14 | Monsters University| Dan Scanlon      | 2013 | 110           |


## 1. Find the title of each film
~~~sql 
SELECT title FROM movies;
~~~
## 2. Find the director of each film

~~~sql 
SELECT director FROM movies;
~~~
## 3. Find the title and director of each film
~~~sql 
SELECT title ,director FROM movies;
~~~

## 4. Find the title and year of each film
~~~sql 
SELECT title ,year FROM movies;
~~~

## 5. Find all the information about each film
~~~sql 
SELECT * FROM movies;
~~~

# EXERCISE - 2

## 1. Find the movie with a row id of 6 
~~~sql
SELECT * FROM Movies where id = 6;
~~~
## 2. Find the movies released in the years between 2000 and 2010 
~~~sql
SELECT * FROM Movies where year between 2000 and 2010;
~~~
## 3. Find the movies not released in the years between 2000 and 2010
~~~sql
SELECT * FROM Movies where year not between 2000 and 2010;
~~~
## 4. Find the first 5 Pixar movies and their release year
~~~sql
SELECT  Title, Year FROM Movies where Id between 1 and 5;
~~~
# EXERCISE-3
## 1. Find all the Toy Story movies
~~~sql
SELECT Title FROM Movies Where Title LIKE"toy%";
~~~
## 2. Find all the movies directed by John Lasseter
~~~sql
SELECT title, director FROM movies WHERE director = "John Lasseter";
~~~
## 3. Find all the movies (and director) not directed by John Lasseter
~~~sql
SELECT title, director FROM movies WHERE director != "John Lasseter";
~~~
## 4. Find all the WALL-* movies
~~~sql

~~~
