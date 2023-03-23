# LegoSet_DataScraping
This is a quick script that makes use of the Selenium Python library to scrape details about lego sets from Brickset.com.
First it scrapes the set IDs by year, then uses these IDs to scrape the individual pages.

Features captured: Set number, Name, Set type, Theme, Theme group, Subtheme, Year released, Pieces, Minifigs, Price (nn USD) and Age range.

For the moment this saves as CSV, the next step is to commit it to an SQL database.
