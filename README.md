# BeautifulSoup-Mars

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

For the first part of this assignment, both BeautifulSoup and Splinter were used to scrape the dedicated website provided for news about Mars. The code is designed to looking for the title and summary elements from each article on the page, and then first display that information within the Jupyter Notebook and then to store those results in a new discionary.

For the second part of this assignment, again both BeautifulSoup and Splinter were used to scrape data from the webpage containing weather data from the Curiosity Rover. After scraping the data, it was stored in a Pandas Dataframe so that it could easily be analyzed, and NumPy for charting visuals from the data.  First, confirmation of the creation of the Dataframe was needed, then the data types were confirmed and then converted to the appropriate data type for analysis.

The analysis focused on answering the following prompts: 
1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
  Find the average the minimum daily temperature for all of the months.
  Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
  Find the average the daily atmospheric pressure of all the months.
  Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
  Consider how many days elapse on Earth in the time that Mars circles the Sun once.
  Visually estimate the result by plotting the daily minimum temperature.

Lastly, after the analysis the dataframe was exported to .CSV.

For this assignment class examples were used, including the Mars News in class practice for the first part of this assignment.  Additionally, I reviewed my copy of Python for Data Analysis: Data Wrangling with pandas, NumPy & Jupyter (https://wesmckinney.com/book/) and used https://codepal.ai/code-reviewer to assit in troubleshooting coding errors.
