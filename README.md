Instagram Social Media Performance Analytics

This project is a data-driven Instagram performance analyzer built in Python.
It automates the insights that marketers typically check manually inside Meta Business Suite, transforming raw engagement metrics into clear, actionable recommendations.

Using a real Instagram analytics dataset, the notebook generates:

- The best performing media type (Reels, Images, Carousels, etc.)
- The best day of the week to post
- The best posting hour
- Top content categories
- Which formats grow followers the most
- A ranked list of top-performing posts
- A fully automated marketing insights summary

This project showcases a blend of marketing strategy and technical analysis, ideal for roles in technical marketing, growth, or data-driven digital marketing.

Tech Stack

- Python
- Pandas (data cleaning, KPI calculations)
- NumPy
- Matplotlib and Seaborn (visual analytics)
- Google Colab / Jupyter Notebook

Dataset Overview

The dataset (Instagram_Analytics.csv) includes key Instagram post metrics:

- post_id
- upload_date
- media_type
- likes, comments, shares, saves
- reach, impressions
- caption_length, hashtags_count
- followers_gained
- traffic_source
- content_category
- Engineered features: engagement_rate, day_of_week, hour

Engagement Rate Formula
engagement_rate = (likes + comments) / impressions
	​
Key Visual Insights
Engagement Rate by Media Type
Which types of content drive the highest engagement?

Engagement Rate by Day of Week
Identify when your audience is most active:

Engagement Rate by Posting Hour
Optimize posting time for maximum reach:

Engagement Rate by Content Category
Understand which content themes resonate most:

Automated Marketing Insights Report
At the end of the notebook, a Python-generated insights report summarizes:

- Best-performing media type
- Best day to post
- Best hour to post
- Top-performing content category
- Content type that gains the most followers
- Highest-performing post (full row of metrics)
This mirrors the type of summary a marketing analyst would provide to a team or client.

How to Run the Project

1. Clone the repository

git clone https://github.com/<your-username>/instagram-performance-analytics.git

2. Open the notebook in:

- Google Colab
- Jupyter Notebook
- VS Code

3. Install dependencies:

pip install pandas numpy matplotlib seaborn

4. Run all cells from top to bottom.

Skills Demonstrated

- Marketing KPI engineering (engagement, follower growth, reach efficiency)
- Data cleaning, transformation, and analysis
- Visualization for marketing strategy
- Extracting actionable insights from social data
- Automating reporting and interpreting real metrics
- Communicating insights clearly to non-technical audiences

Future Enhancements

- Predictive model: Which posts will perform best?
- Hashtag performance analytics
- A mini Streamlit dashboard for interactive marketing reporting
- Week-over-week growth comparisons
- Competitor performance benchmarking
