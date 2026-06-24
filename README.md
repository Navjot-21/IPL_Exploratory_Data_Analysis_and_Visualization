# IPL_Exploratory_Data_Analysis_and_Visualization
# IPL Exploratory Data Analysis & Visualization

##  Project Overview

This project performs Exploratory Data Analysis (EDA) on Indian Premier League (IPL) cricket data to uncover insights related to team performance, player statistics, match outcomes, toss decisions, venue advantages, and scoring patterns.

Using Python's data analysis and visualization libraries, the project transforms raw IPL match and ball-by-ball datasets into meaningful visual insights that can support data-driven decision-making in cricket analytics.

---

##  Objectives

* Clean and preprocess IPL datasets.
* Perform exploratory analysis on matches and deliveries data.
* Identify top-performing batsmen and bowlers.
* Analyze team win percentages across seasons.
* Study the impact of toss decisions on match outcomes.
* Investigate seasonal batting trends.
* Examine venue-based home advantages.
* Analyze death-over scoring performance.
* Generate visualizations for better understanding of IPL trends.

---

##  Dataset Information

The project uses two IPL datasets:

### 1. Matches Dataset

Contains match-level information such as:

* Match ID
* Season
* Teams
* Venue
* City
* Toss Winner
* Toss Decision
* Match Winner
* Player of Match
* Date

### 2. Deliveries Dataset

Contains ball-by-ball information such as:

* Match ID
* Innings
* Over
* Batter
* Bowler
* Batsman Runs
* Extra Runs
* Dismissal Information

---

##  Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

##  Analysis Performed

### Data Cleaning & Preprocessing

* Missing value treatment
* Duplicate removal
* Data type conversion
* Team name standardization
* Venue name standardization

### Feature Engineering

* Total runs calculation
* Boundary identification
* Over phase categorization
* Date feature extraction

### Exploratory Data Analysis

#### 1. Top Run Scorers

Identified the highest run-scoring batters in IPL history.

#### 2. Bowling Economy Analysis

Compared bowlers based on economy rate to identify the most economical performers.

#### 3. Team Win Percentage Analysis

Calculated seasonal win percentages to evaluate team consistency.

#### 4. Toss Impact Analysis

Studied whether winning the toss influences match results.

#### 5. Dismissal Pattern Analysis

Examined common dismissal types among top batsmen.

#### 6. Seasonal Batting Trends

Analyzed scoring trends across IPL seasons.

#### 7. Home Advantage Analysis

Investigated venue-specific team performance and home-ground benefits.

#### 8. Death Over Performance Analysis

Compared team scoring efficiency during overs 16–20.

---

##  Key Insights

* IPL scoring rates have increased significantly over the years.
* Consistent performers dominate batting statistics.
* Home venues provide measurable competitive advantages.
* Toss outcomes alone do not guarantee victory.
* Strong death-over batting often contributes to match success.
* Certain bowlers consistently maintain exceptional economy rates.

---

## 📷 Visualizations Included

* Top Batsmen Bar Chart
* Economy Rate Comparison
* Team Win Percentage Charts
* Toss Impact Visualizations
* Dismissal Pattern Analysis
* Seasonal Trend Line Plots
* Home Advantage Heatmaps
* Death Over Performance Boxplots

---

##  How to Run

1. Clone this repository

```bash
git clone <repository-url>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```bash
IPL_Exploratory_Data_Analysis_and_Visualization.ipynb
```

5. Run all cells sequentially.

---

##  Project Structure

```text
├── IPL_Exploratory_Data_Analysis_and_Visualization.ipynb
├── matches.csv
├── deliveries.csv
├── README.md
```

---

##  Future Enhancements

* IPL Match Winner Prediction using Machine Learning
* Player Performance Forecasting
* Auction Value Prediction System
* Interactive Dashboard using Power BI or Tableau
* Real-Time Cricket Analytics

---



---

##  License

This project is created for educational and academic purposes.
