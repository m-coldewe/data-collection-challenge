# data-collection-challenge
extract information via Splinter and HTML parsing with Beautiful Soup

# Data Collection from Mars News and Weather

## Overview
This project uses web-scrabing to gather and analyze data from outside sources. Utilyzes Splinter Browser, BeautifulSoup, Pandas, and Matplotlib.

## Purpose
This project has two parts. The first part uses Browser and BeautifulSoup, first, to automatically navigate to the webpage and then to scrape the html coding. It extracts the text elements pulled from the website then stores the title and article preview as dictionary pairs within a list.

The second part adds Pandas and Matplotlib. With Splinter, it navigates to the website, then uses BeautifulSoup to scrape the data. From there, it finds the table and isolates the table data to read into a Pandas dataframe. This format allows analyzation to answer the following questions:
1. How many months exist on Mars?
2. How many Martian days worth of data exist in the scraped dataset?
3. What are the coldest and warmest months on Mars (at the location of Curiosity)?
4. Which months have the lowest and hightest atmosphereic pressue on Mars?
5. About how many terrestrial days exist in a Martian year?

## Results
1. How many months exist on Mars? 12
2. How many Martian day's worth of data are there? 1867
3. What is the average low temperature by month?

![min_temp_by_month](https://github.com/m-coldewe/data-collection-challenge/assets/152045367/77593ea1-8cfa-4c5a-94cf-519c6c29cb46)

5. Which months have the lowest and highest atmospheric pressure on Mars?
![presure_by_month](https://github.com/m-coldewe/data-collection-challenge/assets/152045367/a3802ede-5fd7-49bb-8b95-f8d76aaa50ba)

6. How many terrestrial days are there in a Martian year?

![num_terrestrial_days](https://github.com/m-coldewe/data-collection-challenge/assets/152045367/c335b845-34e0-418c-950f-d069abffc2cb)


## Summary
On average, the third Martian month has the coldest minimun temperature on Mars, and the eighth month is the warmest. Atmosphereic pressure is, on average, lowest in the sixth month and highest in the ninth month. 
The disatnce from peak to peark is roughly 1425-750, or 675 days. A year on Mars appears to be around 675 days from the plot. A search on the internet confirms that a Mars year is equivalent to 687 earth days. 
