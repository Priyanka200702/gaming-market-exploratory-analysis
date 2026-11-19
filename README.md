# Video Game Sales Analysis — Exploratory Data Analysis

##  Project Overview

This project explores historical video game sales data to identify trends and patterns across different regions, platforms, genres, and publishers.

The goal is to turn raw sales data into meaningful insights that can help explain historical video game market trends.

## 🎯 Objectives

- Explore and understand the video game sales dataset.
- Identify the most popular gaming platforms and genres across different regions.
- Analyze publisher performance based on total global sales.
- Investigate regional differences in video game preferences.
- Examine the relationship between regional sales figures.
- Analyze Electronic Arts' performance across different genres and platforms.
- Identify potentially strong genre-platform combinations for EA based on historical sales.

## 📂 Dataset

The project uses the **Video Game Sales (vgsales)** dataset.

The dataset contains information about video games, including:

| Column | Description |
|---|---|
| `Rank` | Overall sales ranking |
| `Name` | Name of the video game |
| `Platform` | Gaming platform |
| `Year` | Year of release |
| `Genre` | Video game genre |
| `Publisher` | Game publisher |
| `NA_Sales` | Sales in North America |
| `EU_Sales` | Sales in Europe |
| `JP_Sales` | Sales in Japan |
| `Other_Sales` | Sales in other regions |
| `Global_Sales` | Total worldwide sales |

**Note:** Sales figures are expressed in millions of units.

## 🛠️ Tools and Technologies

- **Python** — Data analysis
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization

## 🔍 Analysis Workflow

### 1. Data Loading and Exploration
- Loaded the dataset and examined its structure.
- Reviewed column names, data types, and descriptive statistics.
- Identified missing values and investigated their distribution.

### 2. Data Cleaning
- Handled missing values in the `Year` and `Publisher` columns.
- Removed records with missing release years for analyses requiring release-year information.
- Replaced missing publisher names with `Unknown` where appropriate.
- Checked the dataset for inconsistencies before proceeding.

### 3. Exploratory Data Analysis
- Examined the distribution of games across platforms, genres, and publishers.
- Identified publishers with the highest number of published games.
- Compared regional and global sales performance.
- Analyzed platform and genre performance across different geographical regions.

### 4. Regional Sales Analysis
Investigated sales patterns across:
- North America
- Europe
- Japan
- Other regions

Compared regional genre and platform performance to identify similarities and differences between markets.

### 5. Correlation Analysis
Examined correlations between regional sales variables to understand how sales across different geographical markets move together.

### 6. Electronic Arts — Focused Analysis
Conducted a more detailed analysis of Electronic Arts by examining:

- Total sales across different genres.
- Total sales across different platforms.
- Average sales by genre and platform.
- Genre-platform combinations across different regions.

This analysis was used to identify historically strong combinations for EA.

## 💡 Key Findings

Some of the key observations from the analysis include:

- **Publisher performance:** Nintendo recorded the highest global sales among publishers in the analyzed dataset, followed by Electronic Arts.
- **Platform performance:** PS2 recorded the highest overall global platform sales.
- **Genre performance:** Action was the leading genre in global sales, followed by Sports and Shooter.
- **Regional differences:** Role-Playing games had particularly strong sales in Japan, while Action and Sports performed strongly in North America and Europe.
- **Regional correlations:** North American and European sales showed a relatively strong positive correlation, suggesting similar movements in sales across these markets.
- **Electronic Arts:** Sports games were a major contributor to EA's historical sales in Europe. The analysis also revealed differences in the strongest genre-platform combinations across regions.

### Electronic Arts: Regional Insights

The EA-focused analysis suggested that:

- **North America, Europe, and Other regions:** Sports games on PS2 appeared among the historically promising genre-platform combinations.
- **Japan:** PS2 showed strong historical performance across several genre-platform combinations. However, identifying the strongest genre was less straightforward because some high-average combinations had relatively small sample sizes.

These findings describe historical sales patterns and should not be interpreted as predictions of current market demand.

## ⚠️ Limitations

- The dataset represents historical video game sales and does not reflect the current gaming market.
- Missing release-year records were excluded from analyses requiring year information.
- Average sales can be influenced by a small number of highly successful games.
- Genre-platform combinations may have different sample sizes, making direct comparisons difficult.
- Sales figures represent reported units sold, not revenue, profit, or production costs.
- Correlation indicates association, not causation.
- Historical platform performance does not necessarily indicate future platform success.

## 📁 Project Structure

```text
video-game-sales-analysis/
│
├── requirement.txt
│
├── dataset/
│   └── vgsales.csv
│
├── video_game_sales_eda.ipynb
│
└── README.md
```

*Adjust the file and folder names to match your actual GitHub repository.*

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/Priyanka200702/gaming-market-exploratory-analysis.git
```

2. Navigate to the project directory:

```bash
cd gaming-market-exploratory-analysis
```

3. Install the required libraries:

```bash
pip install requirement.txt
```

4. Open the notebook and run the cells to reproduce the analysis.

## 📚 What I Learned

Through this project, I gained practical experience in:

- Cleaning and preparing real-world datasets.
- Performing exploratory data analysis using Python.
- Aggregating and comparing sales data across multiple dimensions.
- Creating visualizations to communicate analytical findings.
- Using correlation analysis and interpreting its limitations.
- Translating data-driven observations into business-oriented insights.
- Recognizing the importance of sample size when comparing averages.

If you found this project interesting, feel free to explore the notebook and share your feedback!
