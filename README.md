# Techin510-Lab2_HW
Lab2 Homework - Seattle Events, Weather and Lat/Long

Description:
A Python web scraping project to extract and store information about events in Seattle from the visitseattle.org website.

How to Run the Project:
Clone the repository.
Install the required Python libraries: pip install requests beautifulsoup4
Execute the notebook: Lab2_SeattleEvents.ipynb

Learnings and Issues Encountered:

Utilized BeautifulSoup for web scraping and requests for making HTTP requests.
Handled pagination to scrape events from multiple pages.
Extracted event details from both list and detail pages.
Integrated Nominatim API for location lookup and Weather API for weather information.
Stored the scraped data in a CSV file. events_test.csv
The web scraping was done ethically and respectfully. Always checked and complied with the website's terms of service and policies. 

Additionally, APIs used have usage limitations as well.
Finally I read the location information from the event_test.csv file, called the 'https://nominatim.openstreetmap.org/search' and retrieved the latitude and longitude data. Using this information, I called the 'https://api.weather.gov/points/{lat},{lon}' apis to get the weather information and stored the data in the 'events_weather_data.csv' file, since all the locations are in Seattle area, the weather forecast seems to be the same. However, it can be noted that the latitude and longitude information is different for all these locations. 

