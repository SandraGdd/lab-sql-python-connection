![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Connecting Python to SQL

<details>
  <summary>
   <h2>Learning Goals</h2>
  </summary>

  This lab allows you to practice and apply the concepts and techniques taught in class. 

  Upon completion of this lab, you will be able to:
  
- Write a Python script to connect to a relational database using the appropriate Python library and query it using SQL commands.

  <br>
  <hr> 

</details>

<details>
  <summary>
   <h2>Prerequisites</h2>
  </summary>

Before this starting this lab, you should have learnt about:

- Basic SQL queries
- Python and Pandas 
- Data Wrangling, which involves tasks such as grouping, aggregating, dealing with indexes, renaming columns, merging data and performing calculations.
 
  <br>
  <hr> 

</details>


## Introduction

Welcome to the Connecting Python to SQL lab!

In this lab, you will be working with the [Sakila](https://dev.mysql.com/doc/sakila/en/) database on movie rentals. Specifically, you will be practicing how to do basic SQL queries using Python. By connecting Python to SQL, you can leverage the power of both languages to efficiently manipulate and analyze large datasets. Throughout this lab, you will practice how to use Python to retrieve and manipulate data stored in the Sakila database using SQL queries. Let's get started!

## Challenge

In this lab, the objective is to identify the customers who were active in both May and June, and how did their activity differ between months. To achieve this, follow these steps:

1. Establish a connection between Python and the Sakila database.

2. Write a Python function called `rentals_month` that retrieves rental data for a given month and year (passed as parameters) from the Sakila database as a Pandas DataFrame. The function should take in three parameters:

	- `engine`: an object representing the database connection engine to be used to establish a connection to the Sakila database.
	- `month`: an integer representing the month for which rental data is to be retrieved.
 


