# 100 Most Asked Power BI DAX & Excel Functions for Data Analyst Interviews

## 📌 Overview
This document lists the **top 100 DAX functions** used in **Power BI** and **Excel formulas/functions** frequently asked in **Data Analyst interviews**.  
It’s organized into **Power BI DAX Functions** and **Excel Functions**, with short descriptions and common usage examples.

---

## 🟢 Power BI – Most Commonly Asked DAX Functions

### 📊 Aggregation Functions
1. `SUM()` – Returns the sum of a column.  
2. `SUMX()` – Row-by-row sum over a table expression.  
3. `AVERAGE()` – Returns the average of a column.  
4. `AVERAGEX()` – Calculates average over a table expression.  
5. `MIN()` – Returns the smallest value.  
6. `MAX()` – Returns the largest value.  
7. `COUNT()` – Counts numbers in a column.  
8. `COUNTA()` – Counts non-blank values.  
9. `COUNTROWS()` – Counts rows in a table.  
10. `DISTINCTCOUNT()` – Counts unique values.

### 📅 Date & Time Functions
11. `TODAY()` – Returns today’s date.  
12. `NOW()` – Returns current date/time.  
13. `DATE()` – Creates a date from year, month, day.  
14. `DATEDIFF()` – Returns difference between two dates.  
15. `YEAR()` – Extracts year from a date.  
16. `MONTH()` – Extracts month from a date.  
17. `DAY()` – Extracts day from a date.  
18. `WEEKDAY()` – Returns day of week number.  
19. `WEEKNUM()` – Returns week number in year.  
20. `EOMONTH()` – Returns last day of month.

### 🎯 Filter & Iterator Functions
21. `CALCULATE()` – Changes filter context for calculations.  
22. `FILTER()` – Returns filtered table.  
23. `ALL()` – Removes filters from columns/tables.  
24. `ALLEXCEPT()` – Removes filters except specified columns.  
25. `ALLSELECTED()` – Removes filters but respects visuals.  
26. `KEEPFILTERS()` – Retains existing filters in calculation.  
27. `REMOVEFILTERS()` – Clears filters on specified columns.  
28. `VALUES()` – Returns unique values from a column.  
29. `SELECTEDVALUE()` – Returns selected value (or default).  
30. `HASONEVALUE()` – Checks if one value is in the context.

### 🧮 Logical Functions
31. `IF()` – Conditional logic.  
32. `IFERROR()` – Returns alternative if error.  
33. `SWITCH()` – Multiple condition check.  
34. `AND()` – Logical AND.  
35. `OR()` – Logical OR.  
36. `NOT()` – Logical NOT.  
37. `ISBLANK()` – Checks if value is blank.  
38. `ISEMPTY()` – Checks if table has no rows.  
39. `ISFILTERED()` – Checks if column/table is filtered.  
40. `CONTAINS()` – Checks if a table contains a row with given values.

### 🔗 Relationship & Lookup Functions
41. `RELATED()` – Gets related value from another table.  
42. `RELATEDTABLE()` – Returns table related to current row.  
43. `LOOKUPVALUE()` – Finds value in a table based on conditions.  
44. `USERELATIONSHIP()` – Activates an inactive relationship.  
45. `CROSSFILTER()` – Changes filter direction between tables.

### 📐 Math & Statistical Functions
46. `ROUND()` – Rounds number to decimal places.  
47. `ROUNDUP()` – Rounds up.  
48. `ROUNDDOWN()` – Rounds down.  
49. `CEILING()` – Rounds up to nearest multiple.  
50. `FLOOR()` – Rounds down to nearest multiple.  
51. `ABS()` – Returns absolute value.  
52. `DIVIDE()` – Safe division handling divide-by-zero.  
53. `MOD()` – Remainder after division.  
54. `POWER()` – Raises number to power.  
55. `SQRT()` – Square root.

### 🗂 Text Functions
56. `CONCATENATE()` – Joins two text strings.  
57. `CONCATENATEX()` – Joins values from a table expression.  
58. `LEFT()` – Returns first N characters.  
59. `RIGHT()` – Returns last N characters.  
60. `MID()` – Extracts substring.  
61. `TRIM()` – Removes spaces.  
62. `REPLACE()` – Replaces part of text with new text.  
63. `SUBSTITUTE()` – Replaces text occurrences.  
64. `UPPER()` – Converts to uppercase.  
65. `LOWER()` – Converts to lowercase.  
66. `LEN()` – Returns length of text.  
67. `SEARCH()` – Finds position of substring.  
68. `FIND()` – Finds position (case-sensitive).

### 🔍 Ranking Functions
69. `RANKX()` – Ranks items in a table.  
70. `TOPN()` – Returns top N rows by expression.

### 📊 Table Manipulation
71. `ADDCOLUMNS()` – Adds calculated columns to a table.  
72. `SUMMARIZE()` – Creates summary table.  
73. `SUMMARIZECOLUMNS()` – Creates summary table with filters.  
74. `GROUPBY()` – Groups table by columns.  
75. `UNION()` – Combines tables.  
76. `EXCEPT()` – Rows in one table but not another.  
77. `INTERSECT()` – Common rows between tables.  
78. `CROSSJOIN()` – Cartesian product of two tables.  
79. `GENERATE()` – Combines each row of table with another table.  
80. `SELECTCOLUMNS()` – Returns table with specific columns.

---

## 🟠 Excel – Most Commonly Asked Functions/Formulas

### 📊 Lookup & Reference
81. `VLOOKUP()` – Vertical lookup.  
82. `HLOOKUP()` – Horizontal lookup.  
83. `XLOOKUP()` – Modern lookup replacing VLOOKUP/HLOOKUP.  
84. `INDEX()` – Returns value by row/column index.  
85. `MATCH()` – Finds position of value.  
86. `OFFSET()` – Returns range offset from reference.  
87. `CHOOSE()` – Returns value from list.

### 📅 Date & Time
88. `TODAY()` – Returns today’s date.  
89. `NOW()` – Returns current date/time.  
90. `DATE()` – Creates date from Y, M, D.  
91. `DATEDIF()` – Returns difference between dates.  
92. `EOMONTH()` – End of month date.  
93. `TEXT()` – Formats numbers/dates as text.

### 🧮 Math & Statistical
94. `SUM()` – Sums values.  
95. `SUMIF()` – Sums with condition.  
96. `SUMIFS()` – Sums with multiple conditions.  
97. `AVERAGE()` – Returns average.  
98. `AVERAGEIF()` – Average with condition.  
99. `AVERAGEIFS()` – Average with multiple conditions.  
100. `ROUND()` – Rounds number to decimals.  
101. `ROUNDUP()` – Rounds up.  
102. `ROUNDDOWN()` – Rounds down.  
103. `ABS()` – Absolute value.  
104. `POWER()` – Number to power.  
105. `SQRT()` – Square root.

### 🧾 Text
106. `CONCAT()` – Joins multiple text strings.  
107. `TEXTJOIN()` – Joins text with delimiter.  
108. `LEFT()` – First N characters.  
109. `RIGHT()` – Last N characters.  
110. `MID()` – Substring.  
111. `TRIM()` – Removes spaces.  
112. `LEN()` – Length of text.  
113. `UPPER()` – Uppercase.  
114. `LOWER()` – Lowercase.  
115. `PROPER()` – Capitalizes each word.  
116. `REPLACE()` – Replace part of string.  
117. `SUBSTITUTE()` – Replace all occurrences.  
118. `SEARCH()` – Position of substring.  
119. `FIND()` – Position (case-sensitive).

### 🧠 Logical
120. `IF()` – Conditional logic.  
121. `IFS()` – Multiple conditions.  
122. `AND()` – Logical AND.  
123. `OR()` – Logical OR.  
124. `NOT()` – Logical NOT.  
125. `IFERROR()` – Returns alternative if error.  
126. `ISERROR()` – Checks if error.  
127. `ISNUMBER()` – Checks if value is number.  
128. `ISTEXT()` – Checks if value is text.  
129. `ISBLANK()` – Checks if cell is empty.

**Author:** Data Analytics Guide  

**License:** MIT
