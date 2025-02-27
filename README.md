##Basic Aggregation Functions

SUM() – Returns the total sum of Sales.

SUMX() - Returns the total sum of Sales with filter function

AVERAGE() – Calculates the mean (arithmetic average) of a column.

AVERAGEX() - Calculates the mean (arithmetic average) of a column with filter some column.

MIN() – Finds the smallest value in a column.

MAX() – Finds the largest value in a column.

COUNT() – Counts the number of values in a column (excluding blanks).

COUNTROWS() – Counts the number of rows in a table.

COUNTBLANK() – Counts the number of blank (null) values in a column.

DISTINCTCOUNT() – Counts the number of unique values in a column.

![Screenshot 2025-02-24 130815](https://github.com/user-attachments/assets/66c2082c-5135-4d27-937b-e5088aeceb88)


Power BI DAX Functions - README

Introduction

This document provides an overview of DAX (Data Analysis Expressions) functions used in Power BI. DAX is a formula language for creating custom calculations in Power BI, Analysis Services, and Power Pivot in Excel.

Table of Contents

What is DAX?

Basic Syntax and Operators

Common DAX Functions

Aggregation Functions

Filter Functions

Logical Functions

Time Intelligence Functions

Table Manipulation Functions

DAX Best Practices

Resources

1. What is DAX?

DAX (Data Analysis Expressions) is a collection of functions, operators, and constants used in formulas to perform calculations and data analysis in Power BI.

2. Basic Syntax and Operators

DAX formulas use operators like:

Arithmetic Operators (+, -, *, /)

Comparison Operators (=, <>, <, >, <=, >=)

Logical Operators (&&, ||, NOT)

Text Operators (& for concatenation)

3. Common DAX Functions

DAX functions can be categorized into multiple types:

Aggregation Functions

Filter Functions

Logical Functions

Date & Time Functions

Statistical Functions

4. Aggregation Functions

These functions perform mathematical calculations on data columns.

SUM( ColumnName )

AVERAGE( ColumnName )

COUNT( ColumnName )

MIN( ColumnName )

MAX( ColumnName )

5. Filter Functions

Used to modify or retrieve specific data based on conditions.

FILTER( Table, Condition )

ALL( Table )

CALCULATE( Expression, Filters )

RELATED( ColumnName )

6. Logical Functions

Logical functions return Boolean values and help in conditional calculations.

IF( Condition, Result1, Result2 )

SWITCH( Expression, Value1, Result1, Value2, Result2, ... )

AND( Condition1, Condition2 )

OR( Condition1, Condition2 )

7. Time Intelligence Functions

Used for date-based calculations like YTD, QTD, etc.

TOTALYTD( Expression, DatesColumn )

TOTALQTD( Expression, DatesColumn )

SAMEPERIODLASTYEAR( DatesColumn )

DATEADD( DatesColumn, Interval, Number )

8. Table Manipulation Functions

Used to create and modify tables dynamically.

ADDCOLUMNS( Table, ColumnName, Expression )

SUMMARIZE( Table, GroupByColumn, [ColumnName, Expression] )

UNION( Table1, Table2 )

NATURALINNERJOIN( Table1, Table2 )

9. DAX Best Practices

Use variables (VAR) to store intermediate calculations.

Optimize performance by avoiding row-by-row calculations.

Prefer SUMX over SUM when iterating over rows.

Use CALCULATE for context modifications.

10. Resources

Microsoft DAX Documentation

Power BI Community

DAX Guide
