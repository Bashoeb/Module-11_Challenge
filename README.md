**Module_11_Challenge Mars Data Scraping and Analysis**

This project has scraping Mars news articles and Mars weather data, and analyzing the collected data. The scraping and analysis tasks are divided into two parts.

**Requirements**

1. Python v3.10.9
2. Install Numpy
3. Install Pandas
4. Install Datetime
5. Install Matplotlib
6. Import seaborn
7. From splinter import Browser
8. From bs4 import BeautifulSoup as soup
9. Import json

   
**Part 1: Scrape and Analyze Mars Weather Data**

1. Open the Jupyter Notebook file named Part_1_Mars_News_Analysis_SyedHasan.ipynb provided. This notebook will be used to perform the scraping of Mars news articles.
2. Use automated browsing techniques to visit the Mars news website and inspect the page to identify the elements to be scraped.
3. Extract the titles and preview text of the news articles from the website and store the scraping results in   Python data structures. Each title-and-preview pair will be stored in a Python dictionary with the keys 'title' and 'preview'.
4. Store all the dictionaries in a Python list.
5. Print the list of scraped data in the Jupyter Notebook and store the output in a JSON file called "Title_Preview.JSON".
   
**Part 2: Design Your Climate App**

1. Open the Jupyter Notebook file named Part_2_Mars_Weather_Analysis_SyedHasan.ipynb provided in the starter code folder. This notebook will be used to scrape and analyze Mars weather data.
2. Use automated browsing techniques to visit the Mars Temperature Data website and inspect the page to identify the elements to be scraped. The URL for the website is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
3. Assemble the scraped data into a Pandas DataFrame with columns matching the headings of the table on the website.
4. Perform the following analyses on the Mars weather data:
5. Determine the number of months that exist on Mars.
6. Calculate the number of Martian days worth of data available in the scraped dataset.
7. Identify the coldest and warmest months on Mars at the location of Curiosity by finding the average minimum daily temperature for each month and plotting the results as a bar chart.
8. Determine the months with the lowest and highest atmospheric pressure on Mars by finding the average daily atmospheric pressure for each month and plotting the results as a bar chart.
9. Estimate the number of terrestrial (Earth) days in a Martian year by visually analyzing the daily minimum temperature data and considering the time it takes for Mars to circle the Sun once.
10. Export the DataFrame containing the analyzed data to a CSV file.
    
**References**

The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
