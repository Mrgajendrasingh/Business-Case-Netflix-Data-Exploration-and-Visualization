# 🎬 Business Case: Netflix – Data Exploration and Visualization

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?logo=python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

---

# 📌 Project Overview

Netflix is one of the world's leading video streaming platforms with over **222 million subscribers** worldwide. Understanding viewing trends, content distribution, and regional preferences is essential for making strategic decisions regarding content acquisition and production.

In this project, I performed **End-to-End Exploratory Data Analysis (EDA)** on Netflix's content dataset using **Python, Pandas, NumPy, Matplotlib, and Seaborn** to uncover actionable business insights.

---

# 🎯 Business Problem

Netflix wants to answer the following questions:

- Which countries contribute the most content?
- Which genres are most popular?
- Should Netflix focus more on Movies or TV Shows?
- How has content grown over time?
- What movie duration is preferred?
- Which audience rating dominates the platform?
- How can Netflix expand its business using data-driven insights?

---

# 📂 Dataset Information

| Feature | Description |
|----------|-------------|
| Dataset | Netflix Movies & TV Shows |
| Total Records | ~8,800+ Titles |
| Features | 12 |
| Format | CSV |

### Dataset Columns

- Show ID
- Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed In (Genre)
- Description

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📁 Project Structure

```text
Business-Case-Netflix-Data-Exploration-and-Visualization/

│
├── data/
│   └── netflix.csv
│
├── notebooks/
│   └── Netflix_EDA.ipynb
│
├── images/
│   ├── top_countries.png
│   ├── top_genres.png
│   ├── movies_vs_tvshows.png
│   ├── content_added_per_year.png
│   ├── movie_duration_distribution.png
│   ├── movie_duration_boxplot.png
│   └── ratings_distribution.png
│
├── README.md
└── requirements.txt
```

---

# 🔄 Project Workflow

## Stage 1 — Data Exploration

- Understanding dataset shape
- Checking data types
- Summary statistics
- Missing value analysis
- Duplicate check
- Value counts

---

## Stage 2 — Data Cleaning

- Converted `date_added` into datetime format
- Extracted Year, Month, Weekday
- Handled missing values
- Split multi-value columns
  - Country
  - Cast
  - Genre
- Cleaned Movie Duration column

---

## Stage 3 — Data Visualization

- Top Countries
- Top Genres
- Movies vs TV Shows
- Content Added Per Year
- Movie Duration Distribution
- Movie Duration Outliers
- Rating Distribution

Each visualization includes:

- Business Question
- Observation
- Business Insight
- Recommendation

---

# 📊 Key Visualizations

## 1️⃣ Top Countries

## 1️⃣ Top Countries

<p align="center">
  <img src="images/top_countries.png" width="900">
</p>

### Observation

- United States contributes the highest number of Netflix titles.
- India is the second-largest content producer.

### Business Insight

The United States remains Netflix's strongest content market, while India represents a rapidly growing market.

### Recommendation

Continue investing in U.S. productions while expanding original content in India.

---

## 2️⃣ Top Genres

![Top Genres](<img width="962" height="406" alt="image" src="https://github.com/user-attachments/assets/6b55ff32-e7f9-4f6b-ae1a-e6010cd969bd" />
)

### Observation

International Movies dominate the platform.

### Business Insight

Netflix attracts a diverse global audience through multilingual and international content.

### Recommendation

Increase investment in regional and multilingual productions.

---

## 3️⃣ Movies vs TV Shows

![Movies vs TV Shows](<img width="615" height="337" alt="image" src="https://github.com/user-attachments/assets/c51cb5a1-719c-413c-b76e-b88f1507ef22" />
)

### Observation

Movies account for nearly **70%** of the Netflix catalog.

### Business Insight

Movies remain Netflix's primary acquisition strategy.

### Recommendation

Continue investing in movies while selectively expanding high-performing TV Shows.

---

## 4️⃣ Content Added Per Year

![Content Added](<img width="962" height="422" alt="image" src="https://github.com/user-attachments/assets/db2ac998-fa07-4d11-9d0f-ad7300e19a46" />
)

### Observation

Netflix added the highest number of titles in **2019 (2,016 titles)**.

### Business Insight

The platform experienced rapid content expansion before 2020.

### Recommendation

Study and replicate successful acquisition strategies used during 2019.

---

## 5️⃣ Movie Duration Distribution

![Movie Duration](<img width="856" height="397" alt="image" src="https://github.com/user-attachments/assets/2ecd31f0-d855-4f29-bd52-ae837cb80e9c" />
)

### Observation

Most movies have a duration between **80–120 minutes**.

### Business Insight

Standard-length movies dominate Netflix's catalog.

### Recommendation

Prioritize producing movies within this preferred duration range.

---

## 6️⃣ Movie Duration Boxplot

![Movie Duration Boxplot](<img width="750" height="332" alt="image" src="https://github.com/user-attachments/assets/59bcb29d-bbfb-4519-bacc-b3fc1d90e2b7" />
)

### Observation

A few extremely long and short movies appear as outliers.

### Business Insight

Most content follows industry-standard runtimes.

### Recommendation

Maintain a balanced mix of standard and niche-length content.

---

## 7️⃣ Rating Distribution

![Ratings](<img width="892" height="407" alt="image" src="https://github.com/user-attachments/assets/0bf3a105-1c88-4969-9fcf-00eb92970f31" />
)

### Observation

**TV-MA** is the most common content rating.

### Business Insight

Netflix primarily targets an adult audience.

### Recommendation

Continue producing mature content while expanding family-friendly programming.

---

# 💡 Key Business Insights

- 🇺🇸 United States is Netflix's largest content market.
- 🇮🇳 India is the second-largest contributor and a high-growth opportunity.
- 🎬 Movies dominate the platform with nearly 70% of total titles.
- 🌍 International Movies are the most common genre.
- 📈 Netflix experienced rapid content expansion in 2019.
- ⏱️ Most movies have a duration between 80–120 minutes.
- 🔞 TV-MA is the dominant content rating, indicating a strong adult audience.

---

# 📈 Business Recommendations

### ✅ Expand Regional Content

Increase investments in India and other emerging markets.

---

### ✅ Continue Movie Production

Movies remain the platform's strongest content category.

---

### ✅ Produce More International Content

International Movies attract diverse global audiences.

---

### ✅ Maintain Standard Runtime

Focus on producing movies within the 80–120 minute duration range.

---

### ✅ Diversify Audience Segments

Balance mature content with more family-friendly programming.

---

# 🚀 How to Run the Project

```bash
git clone https://github.com/yourusername/Business-Case-Netflix-Data-Exploration-and-Visualization.git

cd Business-Case-Netflix-Data-Exploration-and-Visualization

pip install -r requirements.txt

jupyter notebook
```

---

# 📚 Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 👨‍💻 Author

**Gajendra Singh**

- 🐍 Python | SQL | Power BI | Pandas | NumPy | Matplotlib | Seaborn
