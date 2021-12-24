# 25DaysOfDAXFridays

## Introduction
This repository archives the DAX measures I wrote in response to the [25DaysOfDAXFridays Challenge by Curbal](https://curbal.com/25-days-of-dax-fridays-challenge).

## Reflections from participating in this challenge
1. My first time ever learning DAX in an applied and sustained manner. Previous encounters with DAX were limited to creating calculated columns, using implicit measures, and the lovely RELATED function (which relieved me of using VLOOKUP and INDEX/MATCH once I set up the relationships between table.
2. Through Ruth's challenge and tutorial videos as well the Italian duo's  DEFINITIVE GUIDE TO DAX (Russo and Ferreri) , my eyes opened to the creativity and beauty of DAX. The thinking behind writing each line of DAX code, and how the different methods and even sequence of writing the code matters for the DAX engine.
3. Finally, having being in this self-initiated learning/discovery journey in data analytics and data science for the past couple of years, knowing DAX allows me to reinforce my learning. For example, my next step is to see the equivalent of DAX to Tableau's LOD.

## Key Takeaways
1. CALCULATE's "unusual behaviour" . Unusual and yet flexible, powerful in its ability to modify the existing filter context.
2.  Best practices in writing DAX:
  - Use Measures instead of Column Names
  - Use fully qualified TableCol Names, and never associate the Table name with Measures 
  - Organise Measures in its own Table
  - For improved reability and testing code, use VARIABLES 
3. Performance Analyzer to compare speed of different DAX queries .
4. Difference between aggregation functions vs their non-aggregated counterparts (e.g. SUMX vs SUM)
5. VALUES(TableCol)  to return a list (single col table) of unique values e.g. ProductNames, CustomerNames
6. COUNTROWS + VALUES instead of DISTINCT / DISTINCTCOUNT
7. SELECTEDVALUE(TableCol), to return a particular value from a column
8. SUMMARIZECOLUMNS  + SUMMARIZE to query the table. Here's why I realise DAX is also a querying language ala SQL!!!
