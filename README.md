# ETL Project: Marriage & Religion

Team Members:
Jose Lujan
Aygul Matyakubova,
Sameek Naik
Richard Varos


Data Sources:
State Marriage Rates 1990, 1995, 1999-2016

Source: https://data.world/siyeh/state-marriage-rate 

Format: xlsx

 
U.S. Religious Census for 1990, 2000 and 2010.

Source: http://www.usreligioncensus.org/compare.php 

Format: csv

Data Storage:

MySQL

Plan for Analysis:

Merge state marriage rate data with religious census data across multiple years to evaluate potential correlations between these data sources and their progression across two different points in time (1990, 2000 and 2010).
Data cleanup steps involved included dropping rows containing empty values, removing two states considered by the group to be outliers due to their abnormally high values. In addition, we renamed and reorganized columns to improve user readibility. Finally, the datasets were merged and two separate tables were created and loaded into MySQL. 
