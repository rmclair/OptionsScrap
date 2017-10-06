# OptionsScrap
Use Requests module in combination with lxml and Beautiful Soup to scrap data from YahooFinance

I try to comment my code so that the programs are readable.  
I've been working on scrapping data from several websites to organize it for further analysis using other toolkits developed for Python.
This code was developed to pull data from YahooFinance options chains.

The website queries and addresses are organized by two input values: (1) stock ticker and (2) execution date
The execution date isn't explicit and needs to be scrapped from the initial landing page
After retrieving a list of the execution dates the program iterates through the complete list to output relevant details as a csv file.
The code could be further modified to take in a list of stock ticker names, but currently functions for only a single stock ticker string.


