# The Movie DataBase Investigation
## by (Winner Abiodun)

## Dataset Description
> The analysis is based on the dataset gotten from [here](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True).
it contains 21 distinct columns with 10806 rows.

> Data Wrangling was done programmatically. Duplicates and irrelevant columns were dropped. A new column Profit was created and inserted into the dataframe, null values were identified, however the revenue, runtime and budget had zero values which were replaced with NaN and dropped.
Incorrect Data Types were identified and dates were adjusted apropraitely, a new column was cretaed from the data datatype.

> After wrangling the dataFrame became 3854 rows and 10 columns 

>The main purpose of this Analysis is to pose questions and investigate the Data to answer those questions


## Questions and Findings

>The following questions guided the investigation and the FIndings are summarized as follows.

> **WHAT YEARS ARE THE MOST PROFITABLE YEARS IN THE MOVIE INDUSTRY?**

The most profitable years in the movie industry is the year 2015 and the top 5 profitable years are 2015, 1977, 2009, 1980, 2012. While the years 1980-2000 hold the most losses

> **WHAT RELEASE MONTHS RECORD THE HIGHEST NUMBER OF PROFIT?**

The months of May, June, April, November and July hold the highest profit, this indicates that the second quater of every year could encourage profit if it is the target release_month. Movie release should be avoided in the last quater of the year especialy December

> **Which Director should be considered for contracts based on profitability track record**?

Jennifer Lee is the most profitable Director and should be employed. The top 5 including Jennifer are Irwin Winker, David Yates, Pierre coffin and Mike Thurmier. However this is based on general profitability alone.
To determine the class of directors with profits greater than the median profit, we find that the most succesful top 5 directors are  >--Colin Trevorrow, Joss Whedon, Irwin Winkler, Jennifer Lee and Chris Buck.

> **WHAT YEARS ARE THE MOST POPULAR YEARS IN THE MOVIE INDUSTRY?**

The data show that the movie industry enjoyed the most popularity in the years
1972, 2015, 2014, 1994, 1977.
Movies are most likely to be very popular when they are released in the month of March to November and a chunk of popularity is accrued in the second quater of the year. 
The years with the lowest popularity are Between 1960 and 1980.
Movie released in the first quarter and last quater of the year are often unpopular

> **Which director is the most popular?**

The Data reveals Colin Treverrow as the most popular Director

> **Bonus Check**

The Data ws querried to see the movies Colin Treverrow Directed.
His Movies are always released in the second quarter of the year

> **What genres are the most Popular from year to year?**

The dataset shows the most popular genres in each year, with the all time highest of Action and Adventure

> **What genres are Profitable from year to year?**

The dataset shows the most profitable genres in each year, with the all time highest of Action and Adventure

> **What genres are most popular?**

The most popular movies have a genre of Adventure, Science Fiction and Animation.
This also holds that the most unpopular genres are Foreign, Documentary, and Tv movie

> **What particular genres are most Profitable?**

It apears that the most profitable genre is Animation, then Family after which we have the 3 combo we recommended earlier(Adventure, Fantasy and Science Fiction).
The most unprofitable genres are Foriegn, Documentary and Horor

> **What group of genres are asociated with High popularity?**

Movies with genres of Adventure and science fiction are the most popular groups.
Movies involving crime, horror and drama are mostly unpoplar

> **What Group of genres are associated with the highest profit?**

A touch of adventure, science fiction or mystery and fantasy are associated with the most profit.
We might want to avoid Documentaries as they stand out as the most unprofitable

## Limitation

Due to the abseence of a data dictionary, the data was difficult to describe. Some columns were also difficult to work with e.g the votes. The budget, revenue and runtime had about 5000 zero values, hence they were dropped to preserve the intergity of the conclusions since its an analysis on profitability

