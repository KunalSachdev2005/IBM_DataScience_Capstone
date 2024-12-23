# Winning the Space Race with Data Science

## IBM Data Science Capstone Project

This project is the culmination of a six-month IBM Data Science Specialization. The goal was to develop a machine learning pipeline to predict the success of SpaceX Falcon 9 rocket’s first-stage landings. The project combines data collection, analysis, visualization, and machine learning to deliver actionable insights into the factors influencing landing outcomes.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Getting Started](#getting-started)
3. [File Descriptions](#file-descriptions)
4. [Methodology](#methodology)
5. [Key Features](#key-features)
6. [Technologies Used](#technologies-used)
7. [Results](#results)
8. [Acknowledgments](#acknowledgments)

---

## Project Overview

SpaceX’s innovative reusable rocket technology significantly reduces launch costs, making it a leader in the aerospace industry. SpaceX advertises Falcon 9 rocket launches on its website with a cost of $62 million, whereas other providers charge upwards of $165 million per launch. Much of the savings come from SpaceX’s ability to reuse the first stage of the rocket. Therefore, determining if the first stage will successfully land is critical for assessing the cost and feasibility of a launch. This information is invaluable for alternate companies looking to compete with SpaceX in the rocket launch market.

### Objectives

- Identify key factors affecting landing success.
- Explore relationships among launch conditions, payloads, and outcomes.
- Develop interactive tools for analyzing launch data.
- Create a machine learning pipeline to predict the success of first-stage landings.

---

## File Descriptions

| File Name                                                      | Description                                                                            |
| -------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `Dashboard.ipynb`                                              | Creates an interactive dashboard displaying launch success rates and payload outcomes. |
| `Data_Collection_API.ipynb`                                    | Collects data from SpaceX’s API.                                                       |
| `Data_Collection_Web_Scraping.ipynb`                           | Collects data via web scraping from Wikipedia.                                         |
| `Data_Wrangling.ipynb`                                         | Cleans and processes the collected data.                                               |
| `EDA_DataViz.ipynb`                                            | Performs exploratory data analysis (EDA) using visualization tools.                    |
| `EDA_SQL_SQLite.ipynb`                                         | Conducts EDA with SQL queries on launch data.                                          |
| `Launch_Sites_Locations_Analysis_Folium.ipynb`                 | Analyzes launch site locations using interactive maps with Folium.                     |
| `ML_Models.ipynb`                                              | Implements machine learning models to predict landing success.                         |
| `Project_Presentation_Data_Science_Capstone_Kunal_Sachdev.pdf` | Final project presentation summarizing findings and results.                           |

---

## Methodology

1. **Data Collection**

   - SpaceX API: Collected launch data using GET requests.
   - Web Scraping: Scraped historical Falcon 9 launch records from Wikipedia.

2. **Data Wrangling**

   - Cleaned and formatted data.
   - Created derived features for analysis.

3. **Exploratory Data Analysis (EDA)**

   - Conducted statistical and visual analysis to identify trends and insights.
   - Used SQL and visualization tools like Matplotlib and Seaborn.

4. **Interactive Visualizations**

   - Built dashboards with Plotly Dash.
   - Created interactive maps with Folium to explore launch site success rates.

5. **Machine Learning Models**

   - Implemented Logistic Regression, KNN, SVM, and Decision Tree classifiers.
   - Tuned hyperparameters with GridSearchCV.
   - Achieved a classification accuracy of 87.5% using the Decision Tree classifier.

---

## Key Features

- **Interactive Dashboard**: Visualizes launch success rates and payload performance.
- **Interactive Maps**: Displays launch site data with proximities to landmarks.
- **Predictive Analysis**: Identifies key factors influencing landing outcomes.

### Suggested Image Placement

- Insert screenshots of the dashboard, including pie charts and scatter plots, here.
- Insert images of the Folium map with launch site markers and success rates.

---

## Technologies Used

- **Data Collection**: `requests`, `BeautifulSoup`
- **Data Analysis**: `Pandas`, `NumPy`, `sqlite3`
- **Visualization**: `Matplotlib`, `Seaborn`, `Plotly`
- **Interactive Tools**: `Dash`, `Folium`
- **Machine Learning**: `Scikit-learn`

---

## Results

- **Key Findings**:
  - Higher payloads increase landing success rates for specific orbits.
  - Certain launch sites exhibit consistently high success rates.
- **Best Model**:
  - Decision Tree Classifier with an accuracy of 87.5%.

Insert confusion matrix and other key visualizations here.

---

## Acknowledgments

This project was completed as part of the IBM Data Science Specialization. Special thanks to IBM and Coursera for providing the resources and guidance for this capstone project.

For further questions, feel free to reach out or explore the repository.

[Project Repository](https://github.com/KunalSachdev2005/IBM_DataScience_Capstone)

