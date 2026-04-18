# Data_Visualization_Project
# 📊 Netflix Content Analysis: Trends and Insights

## 📌 Project Overview

This project analyzes Netflix's content dataset to uncover trends in content distribution, growth patterns, and genre preferences. The goal is to understand how Netflix has evolved over time and how its content strategy varies across regions and categories.

---

## 🎯 Objectives

* Analyze the distribution of Movies vs TV Shows
* Explore content growth over the years
* Identify top contributing countries
* Compare content trends across regions
* Examine genre popularity and diversity

---

## 📂 Dataset

* **Source:** Netflix Titles Dataset
* **Records:** ~8800 entries
* **Key Features:**

  * Type (Movie / TV Show)
  * Country
  * Date Added
  * Genre (`listed_in`)
  * Rating & Duration

---

## 🧹 Data Cleaning

* Removed duplicate records
* Handled missing values using `'Unknown'`
* Converted `date_added` to datetime format
* Extracted `year_added` for time-based analysis
* Split multi-value columns (`country`, `listed_in`) for better insights

---

## 📊 Exploratory Data Analysis (EDA)

This section focuses on identifying patterns and trends using tabular analysis before visualization.

- Movies significantly outnumber TV Shows, indicating a strong skew toward movie content on Netflix.

- The United States contributes the highest number of titles, followed by India, showing a concentration of content production in a few regions.

- A noticeable portion of entries contains missing country information labeled as 'Unknown', which may affect geographic analysis.

- Content additions remain minimal before 2015, suggesting slow early growth of the platform.

- A sharp increase in content is observed after 2016, indicating the beginning of rapid expansion.

- The number of titles peaks around 2019, followed by a decline in subsequent years.

## 📈 Visualizations & Insights

This section builds on the initial analysis by visually representing patterns and extracting deeper insights.

### 1. Movies vs TV Shows
- Movies dominate the platform, with a significantly higher count than TV Shows
- The visual gap highlights Netflix’s stronger focus on movie content

### 2. Distribution by Top Countries
- The United States leads by a large margin compared to other countries
- India is the second-largest contributor, but with a notable gap
- 'Unknown' appears as a major category, indicating missing data that impacts analysis

### 3. Content Growth Over Years
- Minimal growth before 2015
- Rapid expansion begins around 2016
- Peak content addition occurs around 2019
- A decline is observed after the peak period

### 4. Country-wise Content Comparison
- Movies dominate across most countries
- Regional variations exist, with some countries showing relatively higher TV Show proportions
- These differences suggest varying content strategies and audience preferences

### 5. Movies vs TV Shows Over Time
- Movies show a sharper growth trend compared to TV Shows
- TV Shows grow steadily but at a slower pace
- The gap between Movies and TV Shows widens significantly after 2016

### 6. Top Genres
- International Movies and Drama dominate the content library
- Strong emphasis on globally appealing and narrative-driven content
- A mix of genres indicates content diversity beyond mainstream categories



---

## 🔍 Key Findings

* Netflix content is heavily dominated by Movies
* The United States leads in content contribution
* Significant expansion occurred after 2016
* International content plays a major role
* Drama and International Movies are the most prominent genres
* Content distribution varies across regions

---

## 🧠 Conclusion

Netflix has rapidly expanded its content library with a strong focus on Movies and globally distributed content. The platform demonstrates a strategic emphasis on international markets while maintaining dominance in key regions like the United States. The rise in content after 2016 reflects aggressive scaling, while genre trends highlight a preference for widely consumable and story-driven content.

---

## ⚠️ Limitations

* Missing values (e.g., country labeled as 'Unknown')
* Dataset may not reflect the most recent Netflix catalog

---

## 🚀 Future Work

* Analyze ratings and audience preferences
* Explore recommendation systems
* Perform deeper genre-based segmentation

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

---

## 📎 Author

* Yash Verma

---

## ⭐ If you found this project useful, consider giving it a star!
