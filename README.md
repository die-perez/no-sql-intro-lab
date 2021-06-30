# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL? -
    - NoSQL databases (aka "not only SQL") are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.

2. What are some of the common arguments for using a non-relational versus a relational db?
    - the ability to distribute data across multiple servers and regions to make applications resilient, to scale-out instead of scale-up, and to intelligent geo-place data 

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
    - Document databases store data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values.

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?
    - It's easier to maintain dbs where everything is in one file so Mongo's advantage is the ability to store everything in one document based db

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 
    - A SQL db might have 2 tables, one for customer personal info, and the other for the customer acct info like years, account number... with a last name tying both together. The same example in a no-SQL db would pack all of that information into one object.

6. What is an example situation where a Mongo database makes sense versus a non-relational db?
    - Databases with information that ties to one user such as one to many relationships

