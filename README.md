# Module11challenge_datacollection

## Scrape titles and preview text from Mars News

### Use the starter code file "part_1_mars_news.ipynb" and did the following:

1. use automated browsing to visit the Mars News site and inspected which elements to scrape.
2. create a beautiful soup object and use it to extract text elements from the website.
3. extract the titles and preview text of the news articles scraped and store the results in Python data structures; specificially, (1) store each title-and-preview pair in a Python dictionary and give each dictionary two keys as "title' and "preview"; (2) store all the dicionaries in a Python list; (3) and print the list in the notebook.

## Scrape and analyse Mars weather data

### Use the starter code file "part_2_mars_weather.ipynb" and did the following:

1. use automated browsing to visit the Mars temperature data site and inspect the page to identify which elements to scrape.
2. create a beautiful soup object and use it to scrape the data in the HTML table.
3. assemble the scraped data into a Pandas DataFrame with the columns having the same headings as the table on the website.
4. examine the data types and convert the data to the appropriate data types for further analyses. 
5. analyse the ddataset by using Pandas functions and answered the following questions:

    Q: How many months exist on Mars?
    A: 12 months exist on Mars.

    Q: How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    A: total 1867 Martian days worth of data exist in the scraped dataset.

    Q: What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
    A: The coldest month on Mars is the third month and the warmest month on Mars is the eighth month.

    Q: which months have the lowest and the highest atmospheric pressure on Mars?
    A: The sixth month has the lowest atmospheric pressure while the nineth month has the highest atmospheric pressure on Mars.

    Q: About how many terrestial (Earth) days exist in a Martian year? 
    A: The distance from peak to peak is rough between (750-75=675) or (1425-750=675), suggesting about 675 terrestial days exist in a Martian year, which is similar to the number "687" earth days from internet search.

6. export the DataFrame to a CSV file.

## References/acknowledgement
This assignment has been completed primarily with reference to the course materials for Module 11. The help from the teaching team, from the Xpert Learning Assistant at Datacampspot, and from the ChatGPT are acknowledged. 

