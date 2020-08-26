# DBFoundation_Modules-07_Rohan
IT FDN 130 Summer 2020 
Assignment 07 08/23/2020

Explain when you would use a SQL UDF: 

The User Defined Functions in SQL are like functions that accept the parameter, performing complex calculations, and returning the result value. The return value can either be a single scalar value or a result set.      
They allow modular programming      
They allow faster execution      
They can reduce network traffic. 

Explain the differences tween Scalar, inline, and Muti-Statement Functions.  

Scalar: The scalar function accepts any number of parameters and returns one value. The term scalar differentiates a single value from more complex structured values, such as arrays or result sets.

Inline:       The Inline Table-Valued Functions (ITVF): They just return a select statement there is no table variable to mess around with no inserts, no code blocks. Just a select statement  

Multi-Statement Functions:       Your returns syntax explicitly specifies the structure of the return table. This is done by declaring a table variable that will be used to store and accumulate the rows that are returned as the value of the function, Multi-Statement function s can be used to do some very unique things outside the context of a standard select statement.
