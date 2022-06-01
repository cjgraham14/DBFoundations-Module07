**Name:** CJ Graham  
**Date:** May 31, 2022  
**Course:** IT FND 130 A  

**Assignment 7 - SQL Functions**

# **Introduction**

Functions are another way, along with views and stored procedures, to save Select statements for later reference. Many SQL editing programs have a variety of built-in functions that use widely understood nomenclature to carry out simple manipulations of data (for example a SUM function that adds values together). People can also write their own functions, which can be passed information to provide outputs that the user might find useful.

## **User Defined Functions**

A User Defined Function is one of those custom functions that can be written to accept a value, perform a calculation, and return a result. They allow for modular programming as they can be stored in a database and used over and over again whenever the same manipulation or calculation needs to be performed. They also reduce the complexity of code and make executing code faster and easier. You might use a user defined function to produce a table based on the value from a particular field that the function is passed as a way of grouping results, for example.

## **Scalar, Inline, and Multi-Statement Functions**

There are multiple variations on the way we use functions, with the main differences being the quantity of data returned by the function. A Scalar function returns a single data value of the type specified by the function’s return clause. These are helpful for performing calculations in order to receive one actionable result. Inline functions, on the other hand, operate largely like a View. They can return multiple fields of data, but can only contain a single select statement. A Multi-Statement Function, on the other hand, can contain one or many select statements and can return multiple fields of data in the same way that an Inline function can.

## **Summary**

Functions in SQL, as with all other programming languages, are used to make repeatable, atomic chunks of code that perform the same actions whenever they are called. While they cannot be used to alter the contents of tables (like you can do with stored procedures) they are highly useful for interacting with large datasets.
