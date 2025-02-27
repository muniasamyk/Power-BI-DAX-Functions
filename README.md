1)Aggregation Functions

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

2)Text Functions

CONCATENATE( Text1, Text2 ) – Joins two text strings.

LEFT( Text, NumChars ) – Extracts a specified number of characters from the start of a text string.

RIGHT( Text, NumChars ) – Extracts a specified number of characters from the end of a text string.

MID( Text, StartNum, NumChars ) – Extracts a substring from a text string.

LEN( Text ) – Returns the length of a text string.

UPPER( Text ) – Converts a text string to uppercase.

LOWER( Text ) – Converts a text string to lowercase.

TRIM( Text ) – Removes extra spaces from text.

REPLACE( Text, StartNum, NumChars, NewText ) – Replaces part of a text string with another string.

SUM( text ) - Length of text 


![Screenshot 2025-02-25 202207](https://github.com/user-attachments/assets/0fa9372d-c2d2-4b5a-bea1-9338dbd4d5d8)

3)Date Function

DATEADD( DatesColumn, Interval, Number ) – Shifts dates by a specified number of intervals (e.g., days, months, years).

EDATE( StartDate, Months ) – Returns the date that is a specified number of months before or after a given date.

EOMONTH( StartDate, Months ) – Returns the last day of the month that is the given number of months before or after a specified date.

TODAY() – Returns the current date.

NOW() – Returns the current date and time.

DATE( Year, Month, Day ) – Returns a specific date based on year, month, and day.

DATEDIFF( StartDate, EndDate, Interval ) – Returns the difference between two dates in specified units (e.g., days, months, years).

FIRSTDATE( DatesColumn ) – Returns the first date in a column.

LASTDATE( DatesColumn ) – Returns the last date in a column.

DATESBETWEEN( DatesColumn, StartDate, EndDate ) – Returns dates within a specified range.

DATESINPERIOD( DatesColumn, StartDate, Number, Interval ) – Returns a set of dates shifted by a specified interval.

![image](https://github.com/user-attachments/assets/bb46ce54-43fe-4d60-9e95-14d5cd2f144f)

4)Logical Functions

IF( Condition, Result1, Result2 ) – Returns Result1 if the condition is TRUE, otherwise returns Result2.

SWITCH( Expression, Value1, Result1, Value2, Result2, ..., DefaultResult ) – Evaluates an expression against a list of values and returns the corresponding result.

AND( Condition1, Condition2 ) – Returns TRUE if both conditions are TRUE, otherwise returns FALSE.

OR( Condition1, Condition2 ) – Returns TRUE if at least one condition is TRUE, otherwise returns FALSE.

NOT( Condition ) – Returns TRUE if the condition is FALSE, and vice versa.

![image](https://github.com/user-attachments/assets/686a1816-e7db-4340-b7a3-4c0b8b7e6a86)


