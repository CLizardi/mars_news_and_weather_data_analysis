# Introduction

This is a web scraping project that retrieves and analyzes news titles and previews from the Mars Exploration Program website, as well as temperature and atmospheric pressure data from the Mars Temperature Data Site. The project uses Python and several libraries, including Splinter and BeautifulSoup, to automate web browsing and extract data from HTML tables. The extracted data is then stored in a Pandas DataFrame for analysis.

# Deliverable 1: Scraping Titles and Preview Text from Mars News
The first step in this project was to visit the Mars news site at https://static.bc-edx.com/data/web/mars_news/index.html and extract the text elements from the page. A Beautiful Soup object is created from the HTML content, and the text elements are extracted and stored in a list of dictionaries. Each dictionary contains two keys: title and preview, which correspond to the title and preview text of a single news article.

#Deliverable 2: Scraping and Analyzing Mars Weather Data
The second step in this project was to visit the Mars Temperature Data Site at https://static.bc-edx.com/data/web/mars_facts/temperature.html and extract the data from the HTML table. A Beautiful Soup object is created from the HTML content, and the rows of data are extracted and stored in a list. The list is then converted into a Pandas DataFrame for analysis.

The data types of the columns are then examined, and any necessary conversions are performed to cast the data into the appropriate datetime, int, or float data types.

Finally, the DataFrame is analyzed using Pandas functions to answer several questions about the weather data on Mars:

How many months are there on Mars?
How many Martian days' worth of data are there?
What is the average low temperature by month?
Which months have the lowest and highest atmospheric pressure on Mars?
About how many terrestrial (Earth) days exist in a Martian year?

# Conclusion
This project demonstrates the use of web scraping and data analysis techniques to retrieve and analyze news and weather data from websites. The results of the analysis provide insights into the conditions on Mars, and the project can be expanded to include additional data sources or analysis techniques as desired.
