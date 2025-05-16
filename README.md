# Youtube_Trending_Video-Analytics

 📌 Objective
This project analyzes trending YouTube videos across multiple countries to uncover patterns in content type, viewer preferences, and sentiment in video titles.



## 🧰 Tools Used
- **Python** (Pandas, Seaborn, Matplotlib, TextBlob)
- **Power BI** (Visual Dashboards)
- **Excel** (optional preprocessing)



## 📁 Dataset
- Source: [YouTube Trending Datasets from Kaggle](https://www.kaggle.com/datasets)
- Cleaned and merged multiple CSV files across regions.



## 🛠️ Steps Involved

1. **Data Cleaning**  
   - Removed duplicates and missing data  
   - Standardized date formats  
   - Mapped `category_id` to category names

2. **Sentiment Analysis**  
   - Used `TextBlob` to extract sentiment from video titles  
   - Labels: `Positive`, `Neutral`, `Negative`

3. **Data Visualization (Power BI)**  
   - Pie chart: Sentiment distribution  
   - Stacked bar: Region-wise sentiment comparison  
   - Bar chart: Average views by category  
   - Time-series: Video trending duration



## 📈 Results
- **Positive** sentiment titles are most common in trending videos  
- **Music** and **Entertainment** are the most viewed categories  
- Viewer engagement increases during weekends



## 📂 Deliverables
- `cleaned_youtube.csv` – Cleaned dataset  
- `sentiment_analysis.py` – Sentiment labeling script  
- Power BI `.pbix` dashboard  
- Final PDF report


## ✅ Conclusion
This project demonstrates how data analysis and sentiment detection can uncover trends in digital content. Useful for content creators, marketers, and analysts aiming to understand viewer behavior.
