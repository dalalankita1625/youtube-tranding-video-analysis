# YouTube Trending Video Analysis

## 📌 Project Overview

This project analyzes YouTube trending videos to understand video performance, audience engagement, and trending patterns.

The project combines **Python/Pandas for data analysis and preprocessing** with **Power BI for interactive dashboard development**.

The analysis focuses on views, likes, comments, trending dates, publishing time frames, and day-of-week patterns.

---

## 🎯 Project Objectives

- Analyze the performance of trending YouTube videos
- Identify videos with the highest number of views
- Analyze audience engagement through likes and comments
- Study views and comments across different time frames
- Analyze trending patterns over time
- Identify publishing day patterns
- Build an interactive Power BI dashboard

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab
- Power BI
- Power Query

---

## 📊 Dataset

The dataset contains information about YouTube trending videos, including:

- Video ID
- Trending Date
- Video Title
- Channel Title
- Category ID
- Publish Date
- Time Frame
- Published Day of Week
- Publish Country
- Views
- Likes
- Dislikes
- Comment Count
- Comments Disabled
- Ratings Disabled
- Video Error/Removed

---

## 🧹 Data Cleaning

Data preparation was performed using **Power Query** and Python.

The cleaning process included:

- Removing blank rows
- Checking for duplicate records
- Correcting column data types
- Converting trending dates into proper date format
- Converting numeric columns into whole-number data types
- Converting Boolean columns into True/False data types
- Creating a readable category name column
- Validating the cleaned dataset before analysis

---

## 📈 Analysis Performed

### Video Performance

- Total views
- Total likes
- Total comments
- Top 10 videos by views

### Trending Patterns

- Views over time
- Views by time frame
- Comments by time frame
- Videos by published day of week

### Audience Engagement

- Likes as an indicator of audience interaction
- Comments as an indicator of audience interaction
- Comparison of video performance metrics

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was created to present the analysis visually.

### Dashboard Includes

- **Total Views KPI**
- **Total Likes KPI**
- **Total Comments KPI**
- **Views Over Time**
- **Views by Time Frame**
- **Comments by Time Frame**
- **Videos by Day of Week**
- **Top 10 Videos by Views**

The dashboard provides a quick overview of video performance and trending patterns.

---

## 💡 Key Insights

The analysis helps identify:

- Videos receiving the highest number of views
- Changes in video performance over trending dates
- Time frames associated with higher views
- Time frames associated with higher comments
- Publishing days with more trending videos
- Patterns in audience engagement

---

## 📁 Project Structure

```text
youtube-tranding-video-analysis/
│
├── YouTube_Trending_Video_Analysis.ipynb
├── YouTube_Trending_Video_Analysis.pbix
├── youtube.csv
├── dashboard.png
└── README.md
▶️ How to Run
Python Analysis
Clone or download this repository.
Open YouTube_Trending_Video_Analysis.ipynb.
Open it using Google Colab or Jupyter Notebook.
Make sure the dataset path is correctly configured.
Run the notebook cells sequentially.
Power BI Dashboard
Download YouTube_Trending_Video_Analysis.pbix.
Open the file using Power BI Desktop.
If required, update the dataset file path.
Refresh the data.
🚀 Future Improvements
Use a larger dataset containing multiple countries and categories
Add category-level analysis
Add country-level analysis
Add engagement rate calculations
Add interactive filters and slicers
Perform deeper statistical analysis
Build predictive models for video performance
🏁 Conclusion

This project demonstrates practical experience in data cleaning, exploratory data analysis, data visualization, Power Query, and Power BI dashboard development.

It shows how raw YouTube data can be transformed into meaningful insights about video performance, audience engagement, and trending patterns.


### Your final GitHub repository should contain:

```text
📁 youtube-tranding-video-analysis
│
├── 📓 YouTube_Trending_Video_Analysis.ipynb
├── 📊 YouTube_Trending_Video_Analysis.pbix
├── 📄 youtube.csv
├── 🖼️ dashboard.png
└── 📖 README.md
