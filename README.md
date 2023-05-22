# Mission-to-Mars

# Mars Data Scraping and Analysis

This project involved web scraping and data analysis of Mars-related data. It includes two parts: scraping Mars news articles and analyzing Mars weather data. The project utilizes Python, Beautiful Soup, Splinter, and Pandas libraries for web scraping, data extraction, analysis, and visualization.

## Part 1: Scrape Titles and Preview Text from Mars News

In this part, I used automated browsing and Beautiful Soup to visit the Mars NASA news site and extract the titles and preview text from the news articles. The steps involved are as follows:

1. Visit the Mars NASA news site using automated browsing.
2. Create a Beautiful Soup object and extract the text elements from the website.
3. Store the titles and preview text of the news articles in Python data structures.
4. Print the list of dictionaries containing the titles and preview text.

## Part 2: Scrape and Analyze Mars Weather Data

In this part, I used automated browsing, Beautiful Soup, and Pandas to scrape and analyze Mars weather data from a temperature data site. The steps involved are as follows:

1. Visit the Mars Temperature Data Site using automated browsing.
2. Create a Beautiful Soup object and scrape the data from the HTML table.
3. Assemble the scraped data into a Pandas DataFrame.
4. Examine and convert the data types of the DataFrame columns.
5. Analyze the dataset by answering several questions using Pandas functions and visualizations:
   - How many months exist on Mars?
     - Number of months on Mars: 12
   - How many Martian days' worth of data exist in the scraped dataset?
     - Number of Martian days worth of data: 1867
   - What is the average low temperature by month?
     - month
        1    -77.160920
        2    -79.932584
        3    -83.307292
        4    -82.747423
        5    -79.308725
        6    -75.299320
        7    -72.281690
        8    -68.382979
        9    -69.171642
        10   -71.982143
        11   -71.985507
        12   -74.451807
   - Which months have the lowest and highest atmospheric pressure on Mars?
     - Coldest month on Mars: 3
     - Hottest month on Mars: 8
   - Estimate the number of terrestrial (Earth) days in a Martian year.
     - Approximate number of terrestrial days in a Martian year: 687.0
6. Export the DataFrame to a CSV file.

## Conclusion

This project demonstrates the process of web scraping and data analysis using Python and relevant libraries. The scraped Mars news articles and analyzed Mars weather data provide valuable insights into the current state and conditions on Mars.
