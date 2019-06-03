# Behavioral-Finance-PS2

For this project, I choose the public traded stocks in the US from CRSP (with Share Code 10 or 11 and Exchange Code between 1 and 3). Since the book to market and size are needed and momentum needs to be calculated, I also choose the ones with Number of Shares Outstanding, Book Value Per Share, and Holding Period Return.

The datasets for this project are:

* CRSP Monthly Stock:
    * Share Code
    * Exchange Code
    * Price
    * Holding Period Return
    * Number of Shares Outstanding

* CRSP/Compustat Merged - Fundamentals Annual
    * BKVLPS -- Book Value Per Share
    * Fiscal Year-End
* CRSP/Compustat Merged Database - Fundamentals Quarterly
    * RDQ -- Report Date of Quarterly Earnings

* CRSP/Compustat Merged Database - Security Daily
    * DIV -- Dividends per Share - Ex Date - Daily (Issue)

* CRSP Daily Stock
    * Share Code
    * Exchange Code
    * Holding Period Return

Since the Dividend data only starts at 1983 and Earnings Announcement data only stars at 1961, I would obtain the data from 1959-01 to 2018-12.

The detailed report could be find here([Code](https://github.com/JiaxiLi1995/Behavioral-Finance-PS2/blob/master/Event_studies.Rmd) [Report](https://github.com/JiaxiLi1995/Behavioral-Finance-PS2/blob/master/Event_studies.md)).