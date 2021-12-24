# 25DaysOfDAXFridays #Curbal

## Introduction
This repository archives the DAX measures I wrote in response to the [25DaysOfDAXFridays Challenge by Curbal](https://curbal.com/25-days-of-dax-fridays-challenge).

## Reflections from participating in this challenge
1. My first time ever learning DAX in an applied and sustained manner. Previous encounters with DAX were limited to creating calculated columns, using implicit measures, and the lovely RELATED function (which relieved me of using VLOOKUP and INDEX/MATCH once I set up the relationships between table. I stumbled upon the challenge quite accidentally as I only occasionally followed Curbal's Youtube videos. For the first 3 days or so, I merely stayed on the sideline as an observer. Later inspired by the community and also an intrinsic drive to constantly learn, I joined the challenge.
2. Through Ruth's challenge and tutorial videos as well as  [DEFINITIVE GUIDE TO DAX by the Italian duo Russo and Ferrero](https://www.sqlbi.com/books/the-definitive-guide-to-dax-2nd-edition/) , my eyes opened to the creativity and beauty of DAX. The logical thinking behind writing each line of DAX code, and how the different methods and even sequence of writing the code matters for the DAX engine.
3. Finally, having started on this self-initiated learning/discovery journey in data analytics and data science for the past couple of years (partly as a neccessity  of work, and then later as more of a self-interest), knowing DAX allows me to strength my learning in the ecosystem. For example, I start to realise there are parallels between CALCULATE and Tableau's LOD. (Indeed, I am thinking whether I can replicate the entire 25days of DAX in Tableau.)

## Key Takeaways in the Learning
1. Understanding what it means by CALCULATE's "unusual behaviour" . Unusual and yet flexible, powerful in its ability to modify the existing filter context.
2. Best practices in writing DAX:
  - Use Measures instead of Column Names
  - Use fully qualified TableCol Names, and never associate the Table name with Measures 
  - Organise Measures in its own Table
  - For improved reability and testing code, use VARIABLES 
3. Performance Analyzer to compare speed of different DAX queries .
4. Difference between aggregation functions (SUMX, MAXX) vs their non-aggregated counterparts (SUM)
5. Using VALUES([TableCol])  to return a list (single col table) of unique values e.g. ProductNames, CustomerNames
6. COUNTROWS + VALUES instead of DISTINCT / DISTINCTCOUNT
7. SELECTEDVALUE([TableCol]), to return a particular value from a column
8. SUMMARIZECOLUMNS  and SUMMARIZE to query the tables to get a smaller table for subsequent manipulations. Here's why I realise that DAX is also a querying language quite like SQL!
