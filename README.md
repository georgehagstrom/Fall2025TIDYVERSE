# Fall 2025 TIDYVERSE

Repository for tidyverse create and extend assignments for DATA 607

# Instructions:

Add a few lines to this readme with your name, the api you selected, and a description of what you did in your document. Modifying the readme could be complicated because other users are also going to be changing it, so make sure to pull in changes if your version is behind before pushing.

# List of Projects


1.  Prof. George I. Hagstrom, EPA AQS API <https://aqs.epa.gov/aqsweb/documents/data_api.html>

2.  Masoud Mahdisoltani, jsDelivr API <https://www.jsdelivr.com/docs/data.jsdelivr.com>

    -   Explores download statistics and version fragmentation patterns for popular JS libraries.

3.  Michael Drake, Open Charge API <https://openchargemap.org/site/develop/api#/>

    -   Downloaded EV charger information for Phoenix, AZ and visualized operator distribution.
    -   Extended Hristiyana Yaneva's analysis of NHL API by looking at player performance.

4.  Abeer Shariff, Open Library API (Authors) <https://openlibrary.org/dev/docs/api/authors>

    -   Open Library (Authors) searches for works by Author.

5.  Hristiyana Yaneva, NHL API <https://gitlab.com/dword4/nhlapi>

    -   Analyzed NHL division competitiveness using current season standings data and visualized point spreads across divisions.
    -   Extended Denise Garbato's diabetes-friendly fruit analysis by examining fat content among low-sugar fruits.

6.  Zoran Glisovic, Open-Meteo API [ttps://open-meteo.com/en/docs/historical-weather-api](https://open-meteo.com/en/docs/historical-weather-api){.uri}

    -   Los Angeles Monthly Average Temperature Trends (1975-2024)
    -   Extended by Masoud Mahdisoltani, Adding rainfall analysis and Mann-Kendall trend testing


7.  Tatyana Titova, USGS API <https://earthquake.usgs.gov/fdsnws/event/1/>

    -   Explored relationship between magnitude and depth for earthquake data over the past 12 months.
    -   Extended by Zoran Glisovic by adding a world map visualization of earthquake locations using latitude, longitude, and depth from the original USGS API data.
    -   Extended by Denise Garbato by examining the relationship between earthquake magnitude and USGS significance scores, including visualization and correlation analysis.

    
8. Denise Garbato — Fruityvice API <https://www.fruityvice.com/>

   - Analyzed nutritional data for fruits using the Fruityvice API to identify diabetes-friendly options (low sugar and carbohydrates per 100g).
   - Extended by Kalel Cascardi by adding API error handling with resp_check_status() to validate successful responses.
 
9. Sarika Gupta, Met Museum API - https://metmuseum.github.io/
 - Analyzed representation of Indian artists across Met Museum departments (not just South Asian art dept) using the museum's open API.
 - Extended AShariff's Open Library API example by analyzing which South Asian authors have the most works listed in Open Library

10. Hamidou Ballo, REST Countries API https://restcountries.com/
    - Analyzed population density across 250+ countries to identify global demographic patterns and regional variations using httr2 for API requests and tidyverse for data processing and visualization.
    - Extended Sarika Gupta's Met Museum API analysis by adding temporal analysis to explore when Indian objects were created, revealing that most date from the 18th-19th century colonial period.

11. Haneefah Sebro, Cat Fact API https://catfact.ninja/
    - Analyzed which words appear most frequently in the entire set of 327 distinct cat facts; identified overarching themes in cat-related knowledge.