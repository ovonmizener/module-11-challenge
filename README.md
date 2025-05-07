# Mars Web Scraping and Data Analysis Project

## Overview

This repository contains a project that demonstrates how to scrape data from web pages related to Mars and analyze that data using Python. The project is divided into two main parts:

1. **Mars News Scraping:**  
   - Scrapes the Mars news website.
   - Extracts news article titles and preview texts.
   - Stores the data as a list of dictionaries (and optionally exports it as a JSON file).

2. **Mars Weather Data Scraping and Analysis:**  
   - Scrapes Mars weather data from an HTML table.
   - Organizes the data into a Pandas DataFrame.
   - Converts data types for proper analysis.
   - Performs analyses such as:
     - Calculating the average minimum temperature by month.
     - Computing the average atmospheric pressure by month.
     - Estimating the number of terrestrial days in a Martian year.
   - Creates visualizations using Matplotlib (bar charts and line graphs) to support the discoveries.

## Repository Contents

- **`part_1_mars_news.ipynb`**  
  A Jupyter Notebook that uses Splinter and Beautiful Soup to:
  - Visit the Mars news site.
  - Scrape the titles and preview texts of Mars news articles.
  - Store and (optionally) export the scraped data.

- **`part_2_mars_weather.ipynb`**  
  A Jupyter Notebook that:
  - Visits the Mars weather data website.
  - Extracts information from an HTML table.
  - Converts the scraped data into a Pandas DataFrame.
  - Analyzes the data by calculating temperature and pressure metrics.
  - Visualizes the results with Matplotlib.
  - Exports the final DataFrame to a CSV file.

- **`mars_weather.csv`**  
  A CSV file containing the cleaned and analyzed Mars weather data.

## Project Purpose

The main goals of this project are to:

- **Enhance Web Scraping Skills:**  
  Learn how to extract data from web pages with differing HTML structures using automated tools (Splinter) and parsers (Beautiful Soup).

- **Develop Data Analysis Techniques:**  
  Transform raw data into structured formats, clean and convert data types using Pandas, and extract meaningful insights.

- **Practice Data Visualization:**  
  Create informative graphs using Matplotlib to visually communicate findings such as temperature trends and atmospheric pressure conditions on Mars.

This project simulates a real-world data acquisition and analysis workflow, serving as a practical exercise to build foundational skills in web scraping, data wrangling, and visualization.

## Project Credits

**All code is my own, some usage of Microsoft Copilot/Github Copilot was leveraged in areas where I got stuck or did not understand next steps.**  

