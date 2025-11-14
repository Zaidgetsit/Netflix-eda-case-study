# 📊 Netflix Business Case Study — Exploratory Data Analysis (EDA)

## 🎯 Objective
The goal of this project is to **analyze Netflix’s catalog of movies and TV shows** to uncover meaningful insights that can help the company make data-driven decisions regarding:
- What type of content (movies vs. TV shows) performs best,
- Which genres and countries contribute most to Netflix’s growth,
- How content trends vary by year, rating, and other factors.

---

## 📁 Dataset Overview
This dataset contains details of **8,807 titles** (movies and TV shows) available on Netflix as of mid-2021.  
It includes information about each title’s **cast, director, country, release year, rating, duration, and genre**.

| Feature | Description |
|:---------|:------------|
| `show_id` | Unique identifier for each title |
| `type` | Indicates whether the entry is a Movie or TV Show |
| `title` | Title of the content |
| `director` | Director(s) of the movie/show |
| `cast` | Leading actors involved |
| `country` | Country of production |
| `date_added` | Date when the content was added to Netflix |
| `release_year` | Year when the content was released |
| `rating` | Content rating (e.g., TV-MA, PG-13, etc.) |
| `duration` | Duration in minutes (for movies) or number of seasons (for TV shows) |
| `listed_in` | Genre or category |
| `description` | Summary description of the content |

---

## 🧩 Tools & Libraries Used
- **Python**
- **NumPy** and **Pandas** — Data Cleaning and Manipulation  
- **Matplotlib** and **Seaborn** — Data Visualization  
- **Jupyter Notebook** — Interactive Analysis Environment  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Data Quality Check
- The dataset contains **12 columns and 8,807 rows**.  
- Missing values were found in several columns such as `director`, `cast`, and `country`.  
- `show_id` and `title` are unique for all records.

---

### 2. Key Insights

#### 📽️ Type of Content
- Movies dominate the platform, accounting for **~70%** of the total titles.
- TV Shows make up the remaining **30%**.

#### 🎬 Top Directors
- **Rajiv Chilaka** leads with **19** directed titles, primarily focused on children’s animated content.

#### 🎭 Leading Actors
- **David Attenborough** appears in **19** Netflix titles, mostly documentaries.

#### 🌎 Countries
- **United States** contributes to **35%** of total content — the largest share.
- Other notable contributors: **India**, **United Kingdom**, **Canada**, and **Japan**.

#### 📅 Date Added
- **January 1, 2020** saw the **highest number of additions (109 titles)** — possibly a bulk update event.

#### 🔞 Ratings Distribution
- Netflix features **17 unique content ratings**.
- The most common rating is **TV-MA (Mature Audience)** — applied to **36%** of total titles.

---

## 📈 Visual Analysis Highlights
- **Bar charts and countplots** were used to explore distributions across content types, countries, and ratings.
- **Word clouds and heatmaps** provided a deeper understanding of genre diversity and correlations among features.
- **Time-series visualizations** revealed content trends across years and seasonal upload patterns.

---

## 💡 Business Recommendations

1. **Invest More in TV Shows:**  
   The growth of long-form series could increase engagement time, especially in emerging markets.

2. **Regional Content Expansion:**  
   Increase production in **India, South Korea, and Japan**, where content demand is rapidly growing.

3. **Family and Teen Segments:**  
   Given the dominance of mature-rated content, diversifying into **PG and PG-13** genres can broaden audience reach.

4. **Content Release Timing:**  
   Strategically adding content at the beginning of the year (like January spikes) could maximize new subscriptions.

---

## 📊 Future Work
- Sentiment analysis of descriptions to assess audience perception.  
- Integration with external datasets (IMDb or Rotten Tomatoes) for deeper performance metrics.  
- Predictive modeling for **genre or rating classification** using supervised ML.

---

## 🧠 Author
**Mohammed Zaid**  
Aspiring Data Scientist | Python | SQL | Machine Learning | Data Visualization  
📫 *Connect with me on [LinkedIn]([https://www.linkedin.com/in/](https://www.linkedin.com/in/mohammed-zaid-332871288/))*  
