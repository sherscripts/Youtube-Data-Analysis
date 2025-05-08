# Youtube-Data-Analysis

A Python-based project that uses the YouTube Data API to analyze video and channel performance. This project tracks daily subscribers and views, cleans and visualizes video metadata, and automates data collection using Windows Task Scheduler.

## 🚀 Features

- 🔍 Fetch video data (views, likes, comments, upload time, etc.) using the YouTube API
- 📈 Analyze subscriber growth and save historical data to a CSV file
- 📊 Generate visualizations: heatmaps, boxplots, growth trends, and scatter plots
- 🧼 Clean and process video titles and descriptions for analysis
- 📅 Schedule daily data collection with Windows Task Scheduler
  
   ## 📸 Visual Highlights

Here are a few visualizations included in the project:

- **Subscriber Growth Over Time**
- **Boxplots for Views, Likes, and Comments**
- **Likes vs Views Correlation**
- **Weekly Views Trend**
- **Heatmap of Feature Correlation**

---

## 🧪 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `google-api-python-client`
- `isodate`
- `datetime`

---

## 🔁 Automation with Windows Task Scheduler

- Windows Task Scheduler is configured to execute the Python script and log output.

This ensures daily snapshots of channel statistics are captured without manual intervention.
