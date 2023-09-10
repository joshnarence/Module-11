
Part 1: Scraping Mars News Titles and Preview Text

In Part 1, you will use web scraping techniques to extract titles and preview text from the Mars News website and optionally save this data in a JSON file.

Automated Browsing: You will start by automating web browsing to visit the Mars News website (URL not provided), and then inspect the page's HTML to identify the elements you need to scrape.

Scraping Titles and Preview Text: Once you've identified the relevant elements, you will use a web scraping library like Beautiful Soup or Scrapy to extract the titles and preview text of the news articles on the Mars News website. You can store this scraped data in Python data structures like lists or dictionaries.

Optional: Save to JSON: If desired, you can save the scraped data to a JSON file for future use or sharing with others. To do this, you'll need to serialize your Python data structures into JSON format and write them to a file.

Part 2: Scraping and Analyzing Mars Weather Data

In Part 2, you will scrape and analyze Mars weather data from a specific URL (https://static.bc-edx.com/data/web/mars_facts/temperature.html). You will create a Pandas DataFrame to organize the data and answer specific questions about Mars weather.

Automated Browsing: You will use automated web browsing to visit the Mars Temperature Data Site and inspect the HTML structure of the page to identify the elements you need to scrape.

Scraping with Beautiful Soup: You will create a Beautiful Soup object and use it to scrape the data in the HTML table. This table likely contains columns such as 'id,' 'terrestrial_date,' 'sol,' 'ls,' 'month,' 'min_temp,' and 'pressure.'

Data Cleaning and Conversion: You will examine the data types of each column and convert them as needed. For example, you might need to convert dates to datetime objects, sols to integers, and temperatures to floats.

Data Analysis: You will analyze the dataset using Pandas to answer specific questions:

How many months exist on Mars?