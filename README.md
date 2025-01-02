# ⚽⚽ Top Football Leagues Scorers Dataset ⚽⚽
** It's about the top scorers of the football league for anyone who loves soccer or sports in general.
                             ![download](https://github.com/user-attachments/assets/489637f0-c471-4289-bb78-36002842de20)



# Exploratory Data Analysis on Football League Data

## Project Description
This project explores football league data spanning the years 2016 to 2020, focusing on player performance, league statistics, and comparisons of iconic players Cristiano Ronaldo and Lionel Messi. The analysis involves cleaning the data, performing exploratory data analysis (EDA), feature engineering, and conducting hypothesis testing to derive meaningful insights.

---

## Dataset Information
- **Dataset Name**: All Leagues Dataset (2016-2020)
- **Description**: This dataset includes player statistics, league details, and match data across multiple leagues.
- **Source**: https://www.kaggle.com/datasets/mohamedhanyyy/top-football-leagues-scorers

---

## Key Features of the Analysis
1. **Data Cleaning**: Addressed missing values and renamed inconsistent entries.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed outliers and trends in key performance metrics.
   - Visualized data distributions and relationships.
3. **Feature Engineering**:
   - Normalized skewed features for enhanced model readiness.
4. **Hypothesis Testing**:
   - Compared performance metrics of Cristiano Ronaldo and Lionel Messi statistically.

---

## Technologies and Libraries Used
- **Programming Language**: Python
- **Libraries**:
  - Pandas
  - Matplotlib
  - Seaborn
  - NumPy
  - Scipy

---

## Steps Performed
1. **Data Import and Exploration**:
   - Imported the dataset and inspected its structure and quality.
2. **Data Cleaning**:
   - Resolved missing values and corrected league naming inconsistencies.
3. **EDA**:
   - Detected outliers in key features such as `xG Per Avg Match` and `Goals`.
   - Conducted detailed player and league-wise performance analysis.
4. **Feature Engineering**:
   - Applied transformations to normalize right-skewed data for variables like `Goals` and `Shots`.
5. **Hypothesis Testing**:
   - Evaluated the statistical difference in goals contribution between Cristiano Ronaldo and Lionel Messi using the Mann-Whitney U Test.

---

## Results and Insights
- **Key Findings**:
  - The null hypothesis that there is no significant difference in goals contribution between Cristiano Ronaldo and Lionel Messi could not be rejected based on the Mann-Whitney U Test results.
  - Trends in goals, matches played, and expected goals (`xG`) were visualized for comprehensive insights.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/AyoubAZIAMIMER/EDA-for-TOP-LEAGUE-SCORERS
   ```
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn numpy scipy
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook FINAL_PROJECT_EDA.ipynb
   ```

---

## Contributors
- Ayoub Aziamimer


