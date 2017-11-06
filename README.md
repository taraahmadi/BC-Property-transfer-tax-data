# BC-Property-transfer-tax-data
BC Property transfer tax data analysis
Property transfer tax data relating to market transactions within the province of BC

BC provincial property transfer tax open data was published by the Ministry of Finance and can be found on Open data BC. 
There are two data sets containing the information obtained from market transactions; 
one is Property Tax Transfer data from June 2016 to December 2016 and the other one is Property Tax Transfer data from to January 2017 to May 2017.

 
So I needed to add the two datasets together, clean them and then start to analyze. Since both data sets were pretty small (less than 40 rows and 13 columns) I cleaned the data manually. 

1.	I check to see if columns and rows match. I found that there are 3 rows in 2017 data that does not exist in 2016 data so I got rid of them.
2.	I changed the format of the month-year column labels from text to date so that the Excel could understand them the way they are.
3.	The format of 2017 data was text (number saved as text) so I changed their format to numbers

After cleaning the data I started to visualize the data using line charts. This can be easily done by selecting the rows and columns that you are interested in and insert a chart. 
Since I was trying to see patterns over time I chose line charts.

Also because my focus was on foreign involvement in residential transactions I found it useful to calculate the percentage of foreign involvement residential transactions from total residential transactions (the very last row).

