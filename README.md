# 📊 Social Media Interaction & Sentiment Analysis on Bluesky Data

## Overview
This project analyzes large-scale **social media data from Bluesky** to study user interactions and sentiment dynamics.  
The original dataset contains the **posting history of 4M+ users (≈81% of all accounts)** with **235M posts**.  
For this analysis, the data was pre-processed and aggregated into smaller, structured subsets to enable efficient exploration in **Jupyter Notebooks with Python, Pandas and Matplotlib**.

## 📂 Dataset Description
The aggregated dataset consists of three parts:

### 1. Author Interactions
Statistics on how posts by specific authors were received.  
- `author`: unique author ID  
- `replied_count`: total replies received  
- `reposted_count`: total reposts received  
- `quoted_count`: total quotes received  

### 2. User Interactions
Summarizes how users engage with others’ posts.  
- `user_id`: unique user ID  
- `replied_count`: replies made to others  
- `reposted_count`: reposts made by the user  
- `quoted_count`: times the user quoted others’ posts  

### 3. User Post Stats per Day
Daily posting activity with sentiment scores.  
- `date`: posting date  
- `user_id`: unique user ID  
- `post_count`: number of posts created that day  
- `mean_sentiment`: average sentiment score (0 = negative, 1 = neutral, 2 = positive)  

⚠️ **Note:** Sentiment scores are only available for English posts. All datasets were filtered accordingly.  

---

## 🎯 Goals
- Load, clean, and preprocess the datasets  
- Explore **user activity patterns** and **interaction behavior**  
- Perform **sentiment analysis** over time  
- Visualize engagement dynamics with Pandas/Matplotlib  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Pandas, NumPy, scipy, scikit-learn/sklearn,statsmodels** 
- **Matplotlib, Seaborn** (visualization)  
- **Jupyter Notebooks** (interactive analysis)  
- **Docker** (containerized environment for reproducibility)  


