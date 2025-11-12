This task asks me to do the following:

1- Use selenium to open and control the website https://books.toscrape.com/
2- On each page find all 20 books listed
3- For every book go to its detail page and collect all available information, such as title, price, stock information, rating, category, product description, image URL, UPC, product type, tax, number of reviews, and more
4- Go back and repeat this for every book on the page
5- Handle pagination by clicking the “Next” button until all pages are scraped "there are 50 pages, 1000 books total"
6- Save all collected data into a pandas DataFrame.
7- From the availability text like "In stock 22 available", extract only the number (for example, 22).
8- Finally calculate descriptive statistics mean, std, min, max, median, etc. for the availability numbers

Use Selenium to scrape all 1000 books, collect every detail from each bookn’s page, store the data in a DataFrame, extract availability counts, and compute descriptive statistics for availability






This Jupyter Notebook demonstrates web scraping, data collection, and visualization using the website [Books to Scrape](https://books.toscrape.com/). 

The tasks include:
1. Extracting image URLs, ratings, titles, and prices for the 20 books on the main page.
2. Organizing the data into a pandas DataFrame.
3. Creating visualizations to explore the data:
   - Number of products per rating
   - Price distribution
   - Title length distribution
   - Price distribution per rating
   - Correlation heatmap of numeric variables
4. Computing descriptive statistics of prices grouped by rating.
