🎓 Student Feedback & Sentiment Analysis Dashboard
📌 Project Overview

This project analyzes student feedback collected from academic courses and college events to understand overall satisfaction and sentiment. Using Data Science, Natural Language Processing (NLP), and Power BI, the project transforms raw feedback data into meaningful insights that help institutions improve course quality and student experience.

🎯 Objectives

Clean and preprocess student feedback data

Analyze rating distributions using weightage columns

Perform sentiment analysis on feedback questions

Create interactive dashboards using Power BI

Generate insights and recommendations for improvement

🗂️ Dataset Description

The dataset is collected in CSV format (exported from a feedback system or Google Form).

Columns Used:

SN – Serial Number

Total Feedback Given – Number of responses received

Total Configured – Total expected responses

Questions – Student feedback text

Weightage 1–5 – Rating distribution

Average / Percentage – Overall score (if available)

Course Name – Name of the course

Basic Course – Course category

🛠️ Tools & Technologies
Tool	Purpose
Python	Data analysis
Pandas	Data cleaning & preprocessing
TextBlob	Sentiment analysis
Matplotlib & Seaborn	Data visualization
Google Colab	Notebook execution
Power BI	Interactive dashboard creation
Power Query	Data transformation
🧹 Data Cleaning & Transformation

Removed null and inconsistent values

Standardized column names

Converted rating columns to numeric format

Created a Calculated Score using rating weightages

Generated sentiment categories (Positive, Neutral, Negative)

🧠 Sentiment Analysis

Sentiment analysis was performed on the Questions column using TextBlob.
Feedback was classified as:

Positive

Neutral

Negative

This helped convert unstructured text into structured insights.

📊 Power BI Dashboard Features

Sentiment distribution (Pie chart)

Average rating by sentiment

Course-wise satisfaction analysis

Feedback count by course

Interactive slicers for filtering

📁 Project Structure
📦 Student-Feedback-Analysis
 ┣ 📊 PowerBI_Dashboard.pbix
 ┣ 📓 Feedback_Analysis.ipynb
 ┣ 📁 data
 ┃ ┗ Student_Satisfaction_Survey.csv
 ┣ 📄 README.md

🚀 How to Run the Project
Python Analysis

Open the notebook in Google Colab

Upload the dataset

Run cells sequentially

Power BI Dashboard

Open PowerBI_Dashboard.pbix

Refresh data if required

Explore visuals using slicers

📈 Key Insights

Most feedback shows positive sentiment

Courses with higher calculated scores received more positive responses

Negative sentiment highlights improvement areas

Interactive dashboards allow easy exploration of feedback trends

💡 Recommendations

Improve pacing and clarity in low-rated courses

Increase interactive and practical sessions

Regularly analyze feedback using automated tools

Use sentiment trends for curriculum planning

📌 Learning Outcomes

Hands-on experience with data cleaning and NLP

Understanding sentiment analysis concepts

Creating interactive dashboards using Power BI

Translating data insights into real-world recommendations

🧾 References

Google Colab Documentation

Pandas & TextBlob Documentation

Power BI Official Documentation

YouTube Channels:

FreeCodeCamp

Krish Naik

Corey Schafer

Codebasics

🙌 Acknowledgment

This project was completed as part of the Future Interns – Data Science & Analytics Internship Program.

⭐ Connect

If you found this project useful, feel free to ⭐ the repository and connect!
