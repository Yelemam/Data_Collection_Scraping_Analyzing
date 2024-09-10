# Data_collection_Scrapping_Analyzing
![web_scrapping](https://github.com/user-attachments/assets/83019d5d-db44-4227-bb36-fa120f257d8a)

# Introduction

 A full web-scraping and data analysis project.In this project 
 I will be collecting data, organizing and storing data, analyzing
 data, and then visually communicating the insights. 
 So far I learned to identify HTML elements on a page, identify 
 their id and class attributes, and use this knowledge to 
 extract information via both automated browsing with Splinter
 and HTML parsing with Beautiful Soup, also learned to scrape 
 various types of information. These include HTML tables and 
 recurring elements, like multiple news articles on a webpage.
 
 ![mars](https://github.com/user-attachments/assets/5e98eee5-e315-4190-b8da-edb1833f6429)


# Deliverables

   • Scrape titles and preview text from Mars news articles.
   • Scrape and analyze Mars weather data, which exists in a table.

# Instruction
# Part 1: Scrape Titles and Preview Text from Mars News

The starter code folder named part_1_mars_news.ipynb was given.
The following steps below was used to scrape the Mars News website.

   1. Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
# Hint
   2. Create a Beautiful Soup object and use it to extract text 
      elements from the website.
      
   3. Extract the titles and preview text of the news articles that 
      was scraped. Store the scraping results in Python data 
      structure as follows:
      
      o Store each title-and-preview pair in a Python dictionary 
        and, give each dictionary two keys: title and preview. 
      o Store all the dictionaries in a Python list.
      o Print the list in your notebook.
      
   4. Optionally, store the scraped data in a file. To do so, export 
      the scraped data to a JSON file. 
      
# Part 2: Scrape and Analyze Mars Weather Data

The starter code folder named part_2_mars_weather.ipynb was given. 
The following steps below was done to scrape and analyze Mars 
weather data.

   1. Use automated browsing to visit the Mars Temperature Data 
      SiteLinks to an external site. Inspect the page to identify 
      which elements to scrape. Note that the URL 
      is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
   
#Hint
   2. Create a Beautiful Soup object and use it to scrape the data in 
      the HTML table. Note that this can also be achieved by using 
      the Pandas read_html function. However, use Beautiful Soup 
      here to continue sharpening your web scraping skills.
   
   3. Assemble the scraped data into a Pandas DataFrame. 
      The columns should have the same headings as the table 
      on the website. Here’s an explanation of the column headings:
      
      o id: the identification number of a single transmission 
        from the Curiosity rover
      o terrestrial_date: the date on Earth
      o sol: the number of elapsed sols (Martian days) since 
        Curiosity landed on Mars
      o ls: the solar longitude
      o month: the Martian month
      o min_temp: the minimum temperature, in Celsius, of a 
        single Martian day (sol)
      o pressure: The atmospheric pressure at Curiosity's location
      
    4. Examine the data types that are currently associated with 
       each column. If necessary, cast (or convert) the data 
       to the appropriate datetime, int, or float data types.
       
# Hint
    5. Analyze your dataset by using Pandas functions to answer
       the following questions:
       o How many months exist on Mars?
       o How many Martian (and not Earth) days worth of data exist 
         in the scraped dataset?
       o What are the coldest and the warmest months on Mars
         (at the location of Curiosity)? To answer this question:
        1. Find the average minimum daily temperature for all 
           of the months.
        2. Plot the results as a bar chart.
           o Which months have the lowest and the highest 
             atmospheric pressure on Mars? 
             
             ![average_pressure](https://github.com/user-attachments/assets/8a5c90e8-453c-4b61-9a4f-cfdb4a6596e9)

        3. Find the average daily atmospheric pressure of all the months.
        4. Plot the results as a bar chart.
           o About how many terrestrial (Earth) days exist in a 
             Martian year? 
             
             ![min_temp](https://github.com/user-attachments/assets/3de02991-8ae0-4b83-9f3a-e2de3863c823)

        5. Consider how many days elapse on Earth in the time that 
           Mars circles the Sun once.
        6. Visually estimate the result by plotting the daily 
           minimum temperature of each observation.
           
     6. Export the DataFrame to a CSV file.

# Table of Contents
   1. part_1_mars_news.ipynb
   2. part_2_mars_weather.ipynb
   3. average_min_temp.png
   4. average_min_pressure.png
   5. min_temp.png
   6. mars_weather.csv
   7. sctapped_news.json
   

