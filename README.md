# Mars Data Exploration Project

## Background
This project involves a comprehensive web-scraping and data analysis challenge. The goal is to scrape data from multiple web sources, organize and analyze the data, and visually communicate insights. This project demonstrates key skills in data collection, storage, and analysis, while leveraging Python libraries such as Beautiful Soup and Pandas.

---

## Deliverables
This project includes two technical deliverables:

1. **Scrape Titles and Preview Text from Mars News Articles**
2. **Scrape and Analyze Mars Weather Data**

---

## Part 1: Scrape Titles and Preview Text from Mars News
### Instructions
1. Open the Jupyter Notebook: `part_1_mars_news.ipynb`.
2. Use Splinter and Beautiful Soup to:
   - Automate browsing of the Mars News website.
   - Extract titles and preview text from the news articles.
3. Store the extracted data in a Python list of dictionaries with the following structure:
   ```python
   [
       {
           'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
           'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."
       },
       ...
   ]

## Part 2: Scrape and Analyze Mars Weather Data

### Instructions
1. Open the Jupyter Notebook: `part_2_mars_weather.ipynb`.

2. Scrape weather data from the Mars Temperature Data Site:
   - URL: [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
   - Use **Beautiful Soup** to parse the HTML data.

3. Assemble the data into a Pandas DataFrame with the following columns:
   - `id`: Identification number of a single transmission.
   - `terrestrial_date`: Earth date.
   - `sol`: Elapsed sols (Martian days) since landing.
   - `ls`: Solar longitude.
   - `month`: Martian month.
   - `min_temp`: Minimum temperature in Celsius.
   - `pressure`: Atmospheric pressure.

4. Clean and convert the data types as needed:
   - Convert columns to appropriate types, such as `datetime`, `int`, or `float`.

5. Perform analysis:
   - **Number of Months on Mars**: Count the unique Martian months.
   - **Days of Data**: Count the number of Martian days in the dataset.
   - **Coldest and Warmest Months**:
     - Calculate the average minimum temperature for each month.
     - Create a bar chart to visualize the results.
   - **Atmospheric Pressure**:
     - Calculate the average atmospheric pressure for each month.
     - Create a bar chart to visualize the results.
   - **Martian Year Length**:
     - Estimate the number of Earth days in a Martian year by plotting daily minimum temperatures and identifying seasonal cycles.

6. Export the final DataFrame to a CSV file.

---

### Insights

#### Minimum Temperature
- Martian temperatures are extremely cold, with slight variations across months.
- The eighth month is the warmest, with an average minimum temperature of -68°C.

#### Atmospheric Pressure
- Atmospheric pressure peaks in the ninth month and is lowest during the fifth and sixth months.
- Pressure correlates with temperature, increasing during warmer months.

#### Martian Year Length
- A visual analysis of temperature patterns suggests a Martian year lasts approximately 700 Earth days.

---

### Files Included
- `part_1_mars_news.ipynb`: Jupyter Notebook for scraping Mars news data.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data.
- `mars_temp_info.csv`: The final dataset from the weather analysis.
- Folder `Images`: Contains 3 charts.

---

#### Python Libraries
- **Splinter**
- **Beautiful Soup**
- **Pandas**
- **Matplotlib**

#### Data Sources
- **Mars News Website**
- **Mars Temperature Data Site**

## Acknowledgments

This project was developed with the assistance of the following resources:

- **Turtoring Session** – Provided guidance on data analysis and README formatting.
- **Xpert Learning Assistant** – Provided guidance on SQLAlchemy and data analysis.
- **GitLab UofT Activities** – Supplied foundational activities and exercises for analysis.
- **ChatGPT** – Assisted with code, explanations, and README formatting.

Thank you to these resources for supporting the development of this project.