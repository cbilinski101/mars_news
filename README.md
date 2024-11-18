[![Python 3.10](https://img.shields.io/badge/python-3.10-blue.svg)](https://docs.python.org/3.10/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-library-brightgreen)](https://www.crummy.com/software/BeautifulSoup/)
[![Requests](https://img.shields.io/badge/Requests-library-blue)](https://docs.python-requests.org/)
[![Pandas](https://img.shields.io/badge/Pandas-library-yellow)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-library-orange)](https://matplotlib.org/)

# Mars Exploration Project

Welcome to the Mars Exploration Project repository! This project includes two primary components: `Mars News` and `Mars Weather`. Below is an overview of the files and their functionalities.

---

## Table of Contents 

- [Project Overview](#project-overview)
- [Insights](#insights)
- [Files](#files)
  - [Part 1: Mars News](#part-1-mars-news)
  - [Part 2: Mars Weather](#part-2-mars-weather)
- [How to Use](#how-to-use)
- [Technologies Used](#technologies-used)
- [License](#license)

---

## Project Overview

The Mars Exploration Project is designed to provide insights into Mars-related news and weather patterns. This project demonstrates web scraping and data analysis techniques using Python.

---

## Insights

### Minimum Temperature
- Martian temperatures are extremely cold, with slight variations across months.
- The eighth month is the warmest, with an average minimum temperature of -68°C.
  
  ![image](https://github.com/user-attachments/assets/cf56604d-233e-4c75-9123-0d0b290757fe)

### Atmospheric Pressure
- Atmospheric pressure peaks in the ninth month and is lowest during the fifth and sixth months.
- Pressure correlates with temperature, increasing during warmer months.
  
![image](https://github.com/user-attachments/assets/32ef76f6-6af3-432d-a303-1bb55f460bab)


### Martian Year Length
- A visual analysis of temperature patterns suggests a Martian year lasts approximately 700 Earth days.
  
![image](https://github.com/user-attachments/assets/9576f17c-b1c5-42ab-be15-9566941938df)


---

## Files

### Part 1: Mars News (`part_1_mars_news.ipynb`)
- Scrapes the latest Mars-related news articles from a designated source.
- Extracts titles, summaries, and other relevant details for further analysis.
- Displays the news in a clean and organized format.

### Part 2: Mars Weather (`part_2_mars_weather.ipynb`)
- Focuses on collecting and analyzing weather data from Mars.
- Visualizes temperature patterns, atmospheric pressure, and other key metrics.
- Provides insights into the Martian climate over time.

---

## How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/cbilinski101/mars_news.git
2. **Install Required Libraries Ensure you have Python installed. Then, install the dependencies:**
   ```bash
   pip install -r requirements.txt
3. **Run Jupyter Notebooks Open the .ipynb files in Jupyter Notebook or Jupyter Lab:**
   ```bash
   jupyter notebook
4. **Explore the Outputs**
  * Run the cells in each notebook sequentially to see the outputs.

--- 

## Technologies Used

- **Python**: Programming language for web scraping and data analysis.
- **Jupyter Notebook**: Environment for running the notebooks.
- **BeautifulSoup** & **Requests**: Libraries for web scraping.
- **Pandas** & **Matplotlib**: Libraries for data manipulation and visualization.

---

## License
This project is licensed under the MIT License.

---

## Acknowledgments

This project was developed with the assistance of the following resources:

- **Turtoring Session** – Provided guidance on data analysis and README formatting.
- **Xpert Learning Assistant** – Provided guidance on and data analysis.
- **GitLab UofT Activities** – Supplied foundational activities and exercises for analysis.
- **ChatGPT** – Assisted with code, explanations, and README formatting. 

---

Feel free to contribute to this project by submitting a pull request or raising an issue. Enjoy exploring Mars!
