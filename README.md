# Swiggy Data Analysis Project

This project is focused on analyzing data related to the food delivery service provided by Swiggy Banglore location. The project aims to provide insights into the trends and patterns in food delivery orders, customer behavior, and restaurant performance to solve problem statement to openremote kitchen restaurant and decide its menu and price in banglore

# Project Overview

The project uses data from Swiggy's food delivery platform to analyze key metrics such as order volume, delivery time, customer ratings, and restaurant ratings. The analysis is performed using Python programming language and various data analysis libraries such as Pandas, NumPy, and Matplotlib, Seaborn

# Data Sources

The data used in this project is obtained from Swiggy's website banglore location requested paged by performing web-scarpping, which includes data related to orders, customers, and restaurants. The data is pre-processed and cleaned to remove any duplicates, missing values, or irrelevant information.

# Approach

Target Website: Identify the structure of Swiggy's restaurant listings for Bangalore using web inspection tools.
Python and BeautifulSoup: Utilize Python's BeautifulSoup library to perform web scraping, extracting relevant data like restaurant names, menus, and ratings.
Data Processing: Organize and store the scraped data, ensuring compliance with ethical guidelines and website terms of use.

# Data Description 
| Restaurant ID | Restaurant Name | Cuisines               | Address                 | Rating | Price | Delivery Review        |
|---------------|-----------------|------------------------|-------------------------|--------|-------|------------------------|
| 1             | Flavours Of Punjab| Burger, Pizza, Pasta   | 123 Main St, Bangalore | 4.5    | 500    |   5000    |
| 2             | Saoji INN   | Indian, Chinese        | 456 Elm Rd, Bangalore  | 4.2    | 250    |  424 |
| 3             | Kebab Junction    | kebab, Seafood       | 789 Oak Ave, Bangalore | 4.8    | 500  |5444 |


# insights

![Screenshot 2023-08-29 231258](https://github.com/MaverickOP/Swiggy-webscrapping/assets/140721563/06811607-6143-430a-85b3-bedbed5af3bc)

Above insights tells us about the top rated restaurants in banglore 

![Screenshot 2023-08-29 231735](https://github.com/MaverickOP/Swiggy-webscrapping/assets/140721563/8f741d29-41f4-4e39-82ce-777988488939)

Above insights tells us about Area wise distribution of restaurants in Banglore 

![Screenshot 2023-08-29 231938](https://github.com/MaverickOP/Swiggy-webscrapping/assets/140721563/ab9081d0-910f-41af-bc65-692f3650a551)

Above insights tells us about the best location to open restaurant after analyzing all other restaurants

# Challenges

Dynamic Content: Swiggy's website likely uses dynamic content loading techniques, such as JavaScript, to load restaurant listings and details. This can make it challenging to capture all the necessary data using traditional scraping methods.

Anti-Scraping Measures: Swiggy may implement anti-scraping measures to prevent automated data collection, such as CAPTCHAs, IP blocking, or user agent detection. Overcoming these measures while maintaining ethical scraping practices can be tricky.

Pagination: If Swiggy displays a large number of restaurants, pagination might be used. Scraping data across multiple pages while handling navigation correctly can be complex.

Incomplete Data: Not all restaurants' information may be immediately visible or loaded on the initial page load. Additional requests or interactions might be required to retrieve complete data.

Data Cleaning: The scraped data might contain inconsistencies, missing values, or inaccuracies. Cleaning the data to ensure its quality and reliability is crucial for meaningful analysis.

# Conclusion 

In conclusion, undertaking a web scraping project focused on Bangalore's location presents both exciting opportunities and noteworthy challenges. Through this endeavor, we've delved into the world of data acquisition and extraction from online platforms, specifically targeting information related to restaurants and services in Bangalore.

While the project's objective was to gather valuable insights into the local food scene, the journey was not without obstacles. The dynamic nature of websites, potential anti-scraping mechanisms, and shifting data structures posed challenges that required adept technical skills and adaptability. Navigating these hurdles demanded a balanced approach that adhered to ethical scraping practices, legal boundaries, and efficient data extraction methodologies.
