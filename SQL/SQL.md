# SQL Basic

## SQL
> standard language designed for managing data in relational database management system
> **Structured Query Language** -- storing, retrieving, managing or manipulating the data inside a relational database management system (RDBMS)

## SQL Syntax
> SQL statement is composed of a **sequence of keywords, identifiers**, etc. terminated by a semicolon (**;**)

>> SELECT emp_name, hire_date, salary 
>> FROM employees 
>> WHERE salary > 5000;

> SQL keywords are **case-insensitive** that means **SELECT** is same as **select**

>> SELECT emp_name, hire_date, salary FROM employees;
>> select emp_name, hire_date, salary from employees;

> SQL support single-line as well as multi-line comments
>> **--** single-line
>> **/* */**

## SQL CREATE DATABASE Statement
> **CREATE DATABASE** database_name;

> #### Creating Database in MySQL
> Step 1: Invoke the MySQL command-line tool
>> $ mysql -u root -p
> Step 2: Creating a MySQL Database
>> $ **CREATE DATABASE** demo; **or**
>> $ **CREATE DATABASE IF NOT EXISTS** demo;
> Step 3: Selecting the Database
>> $ **USE** demo;
