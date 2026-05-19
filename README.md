# 📊 Social Media Engagement Analytics

An end-to-end Python-based data analytics project that cleans, processes, and visualizes over 5,000 data points of social media performance metrics. This repository highlights user behavior trends, content performance, and sentiment patterns using advanced aggregation techniques and visualization libraries.

---

## 🚀 Project Overview
This project processes tracking metrics (likes, comments, shares, impressions) across various dimensions like demographics, device configurations, content themes, and sentiment categories to extract actionable marketing strategies.

### 🛠️ Tech Stack & Libraries
* **Language:** Python 3.12
* **Environment:** Jupyter Notebook / Google Colab
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`, `plotly.express`

---

## 📦 Dataset Features
The dataset contains structural performance metrics including:
* **Identification:** `user_id`, `post_id`
* **Temporal:** `posted_at` (Datetime format)
* **Demographics:** `age`, `gender`, `country`
* **Engagement Metrics:** `likes`, `comments`, `shares`, `impression_count`, `watch_time_sec`, `follower_count`
* **Categorical Fields:** `post_type`, `post_category`, `is_verified`, `device_type`, `sentiment`

---

## 📈 Final Insights Summary

### 📊 1. Content Performance
* **Top Post Format:** **Video** content drives the highest interaction metrics across the platform, leading with an average engagement rate of **135.32%**, closely followed by text posts (**131.04%**).
* **Winning Themes:** Content focused on **Food** (**168.15%**) and **Tech** (**137.70%**) significantly outperforms other themes like Lifestyle.
* **Geographic Hotspots:** Audiences located in **Brazil** demonstrate peak interaction with a staggering **189.02%** engagement rate, followed by **Australia** (**166.81%**).

### 👥 2. User Trends
* **Age Dynamics:** The **18-25** demographic is the most active cohort (**130.04%** engagement), followed closely by the **50+** segment (**128.13%**).
* **The Verification Premium:** Verified accounts generate a higher average engagement rate of **127.14%**, compared to **116.84%** for unverified profiles, proving that status verification builds baseline trust.

### ⏰ 3. Behavioral Insights
* **Peak Visibility Windows:** Impression metrics reach their maximum volume during **Late Night** hours, averaging **50,013 impressions** per post.
* **Device Retention:** Users consuming content on **mobile** devices maintain the longest average watch times (**4,087.83 seconds**), making it the primary target format for deep attention.

### 🧠 4. Sentiment Analysis
* **Emotional Resonance:** Posts reflecting a **Neutral** tone secure the strongest relative response, leading with a **124.98%** engagement rate.
* **Discussion Dynamics:** While positive posts pull strong numbers for likes, **neutral and negative** sentiment posts drive significantly **higher comment volumes** (**1,528.40** and **1,516.09** comments respectively), highlighting their tendency to spark deep user discussions.

---

## 📂 Visualizations Profile
The analysis pipeline includes a minimum of 8 mandatory plots across different frameworks:
1. **Matplotlib:** Scatter (Likes vs Impressions), Line (Daily Engagement Trends), Bar (Posts by Category), Pie (Gender Distribution), Histogram (Age Distribution), and Box plots (Engagement Rate).
2. **Seaborn:** Count Plots, Category Heatmaps, Correlation Matrix, and Violin/Swarm distribution variations.
3. **Plotly:** Interactive Multi-Dimensional Scatters and breakdown Bar Charts.

---

## ⚙️ Execution & Setup

### 1. Clone the Repository
```bash
git clone https://github.com
cd social-media-analytics
```

### 2. Install Dependencies
```bash
pip install pandas matplotlib seaborn plotly
```

### 3. Run the Pipeline
Open the notebook file (`.ipynb`) in your preferred interface or upload it to Google Colab, upload your dataset file `social_media_engagement_5000.csv`, and execute all cells.

```python
# Quick code snippet to read the file with Google Drive integration
from google.colab import drive
drive.mount('/content/drive')
df = pd.read_csv('/content/drive/MyDrive/social_media_engagement_5000.csv')
```

---



