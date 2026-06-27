# 🎬 Netflix Content Analysis (EDA Project)

A data-driven exploration of Netflix’s global catalog to understand how content is structured across countries, genres, ratings, and time.

---

## 📌 Overview

Netflix doesn’t just host content — it curates it strategically.

This project analyzes Netflix’s dataset to understand how its library is built, what dominates its content space, and how its strategy evolves over time.

The goal is simple:  
turn raw data into clear patterns about content behavior.

---

## 🎯 Analysis Focus

Instead of random charts, the analysis is guided by key questions:

- What dominates Netflix: Movies or TV Shows?
- How has content evolved over time?
- Which countries shape Netflix’s library?
- What genres define its identity?
- Who is the platform actually targeting?
- Is content release consistent or pattern-based?

---

## 🧰 Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🧹 Data Preparation

The dataset required cleaning before analysis:

- Missing values handled in cast, director, country, date_added  
- date_added converted into datetime format  
- Extracted year and month for time-based analysis  
- Multi-value columns (country, genre) split for proper aggregation  
- Duration converted into numerical format for analysis  

---

## 📊 Key Insights

- Movies clearly dominate Netflix’s catalog compared to TV Shows  
- Major growth in content occurs after 2015  
- United States contributes the largest share of content  
- Drama and International Movies consistently dominate genres  
- Most content is rated TV-MA and TV-14, indicating an adult-focused platform  
- Movies mostly fall in the 90–120 minute range  
- TV Shows are typically limited to 1–2 seasons  
- Content addition is not linear — it appears in spikes over time  

---

## 📈 Visual Analysis Includes

- Content type distribution (Movies vs TV Shows)  
- Year-wise content growth trend  
- Top countries by content contribution  
- Genre frequency distribution  
- Ratings distribution analysis  
- Movie duration distribution  
- TV show season distribution  
- Missing value heatmap  
- Rating vs content type relationship  
- Duration vs rating distribution  
- Monthly and yearly content heatmap  

---

## 🧠 Final Insight

Netflix behaves less like a content library and more like a **data-driven recommendation system with strategic content planning**.

Its catalog shows:
- strong movie dominance  
- heavy focus on adult/teen audiences  
- global but US-led production structure  
- structured, batch-based content release strategy  

---

## 🚀 How to Run This Project

### 1. Clone repository
git clone https://github.com/your-username/netflix-eda.git

### 2. Move into directory
cd netflix-eda

### 3. Install dependencies
pip install pandas numpy matplotlib seaborn

### 4. Launch notebook
jupyter notebook

### 5. Open file
Netflix_EDA.ipynb → Run all cells

