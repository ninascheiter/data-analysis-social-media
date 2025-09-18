# 📊 Social Media Interaction & Sentiment Analysis on Bluesky Data

## Overview
This project analyzes large-scale **social media data from Bluesky** to study user interactions and sentiment dynamics.  
The original dataset contains the **posting history of 4M+ users (≈81% of all accounts)** with **235M posts**.  
For this analysis, the data was pre-processed and aggregated into smaller, structured subsets to enable efficient exploration in **Jupyter Notebooks with Python, Pandas and Matplotlib**.

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

## Interesting finds
### clustering users
<img width="932" height="725" alt="tsne_usertypes" src="https://github.com/user-attachments/assets/00e9cc05-3cd7-4e6a-be79-d5700f88e6f9" />
- cluster0 = "sharer" - barely quotes or answers, reposts the most but doesn't reply much 
- cluster1 = "discusser" - answers the most but doesnt quote or repost much. actively engages with other posts
- Cluster2 = "Creator" - most quotes, reposts, quoted- and replied-count, most active
### user sentiment per weekday
<img width="1096" height="645" alt="weekdaymood" src="https://github.com/user-attachments/assets/0918641a-09b7-4219-9416-eab43710788a" />
- it seems that Thursday has the most negative impact on the mood of users whereas sunday shows the most improvement on the mood
