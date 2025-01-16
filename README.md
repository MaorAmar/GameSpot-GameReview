# Games Grade Prediction

### Authors:  
**Maor Amar**  
**Or Yehudian**  

---

## Research Question  
**Can we predict the grade of a game based on various characteristics?**  
We explored the impact of attributes such as game name, platform suitability, number of comments, number of likes, and other factors on the grade.

---

## Project Structure  
Our project is divided into the following parts:  
1. **Data Collection**  
2. **Data Cleaning**  
3. **Exploratory Data Analysis (EDA)**  
4. **Machine Learning**

Additionally, the project includes:  
- The dataset in CSV format.  
- A presentation summarizing our findings.

---

## Technologies Used  
- **Python**  
  - Libraries:  
    - `pandas` – for data manipulation and cleaning.  
    - `numpy` – for numerical computations.  
    - `matplotlib` and `seaborn` – for data visualization.  
    - `scikit-learn` – for machine learning models.  
    - `BeautifulSoup` and `requests` – for web scraping.  
- **Jupyter Notebook** – for interactive coding and data analysis.  
- **Git** – for version control.  

---

## Data Collection  
We used web crawling to collect data from the [GameSpot reviews website](https://www.gamespot.com/games/reviews).  
- Initially, we scraped data from the main page.  
- Then, we extracted additional data from individual game links.  

---

## Data Cleaning  
Data cleaning involved several key steps:  
- Dropping null values and duplicates.  
- Handling outliers.  
- Converting string columns to numeric.  
- Addressing specific issues, such as:  
  - Fixing inconsistencies in game release and review dates.  
  - Removing rows for games reviewed after 2022.  
  - Standardizing platform information.  

---

## Exploratory Data Analysis (EDA)  
We visualized and analyzed the data using various plots and graphs, including:  
- Histograms for game grades, release years, and article counts per year.  
- Scatter plots to observe relationships between:  
  - Number of comments, likes, and grades.  
  - Pros and cons in reviews and their impact on grades.  
- Insights:  
  - High comment density was often associated with low grades.  
  - A strong correlation existed between the number of pros/cons and the grade.

---

## Machine Learning  
We built and tested models to predict game grades, achieving improvements in accuracy.  
- **Linear Regression**: Achieved an accuracy of **0.75** (initially) and **0.78** after improvements.  
- Experimented with other algorithms, achieving a similar accuracy of **0.78**.  

---

## Conclusions  
This project allowed us to explore a fascinating topic and uncover relationships between game characteristics and grades.  
Key findings:  
- Positive and negative reviews significantly influence game grades.  
- Comments and likes play a role but require further investigation to establish stronger predictive trends.  

---

If you have feedback or questions, feel free to contact us!

