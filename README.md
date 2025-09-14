📊 ChatGPT Reviews Analysis
📌 Project Overview

This project analyzes 196,000+ customer reviews of ChatGPT to understand overall satisfaction, extract key insights, and identify areas for improvement.

The analysis combines ratings distribution (1–5 stars) with sentiment analysis on review text to provide both quantitative and qualitative insights.

🎯 Objectives

Measure overall customer satisfaction using ratings.

Perform sentiment analysis (Positive, Neutral, Negative) on written reviews.

Identify recurring themes in positive and negative feedback.

Provide actionable business recommendations based on insights.

🗂️ Dataset

Source: ChatGPT Reviews Dataset (196,727 reviews)

Columns:

Review Id → Unique identifier for each review

Review → Text content of the review

Ratings → Rating score from 1 (lowest) to 5 (highest)

Review Date → Date the review was posted

⚙️ Methodology

Data Cleaning

Removed null values and duplicates.

Processed review text for sentiment analysis.

Exploratory Data Analysis (EDA)

Distribution of ratings (1–5 stars).

Time-based trends in reviews.

Sentiment Analysis

Used TextBlob to calculate polarity scores.

Categorized reviews as Positive, Neutral, or Negative.

Visualization

Plots for ratings distribution.

Pie chart for sentiment breakdown.

WordCloud for most common positive/negative words.

📊 Key Results
⭐ Ratings Distribution

5-star: 41.22%

4-star: 23.11%

3-star: 15.33%

2-star: 7.89%

1-star: 12.45%

✅ 64% of reviews are positive (4–5 stars).
⚠️ 20% of reviews are negative (1–2 stars).

😊 Sentiment Distribution

Positive: 55.67%

Neutral: 23.45%

Negative: 20.88%

🔑 Insights

Users love creativity, ease of use, and usefulness.

Pain points include accuracy issues, slow performance, and pricing concerns.

Neutral reviews often request more features or improvements.

📌 Recommendations

Improve accuracy & reliability of responses.

Enhance speed & performance to reduce frustration.

Review pricing strategies and provide more value in premium plans.

Strengthen customer support & onboarding.

🛠️ Tech Stack

Python (pandas, numpy, matplotlib, seaborn, textblob, wordcloud)

Jupyter Notebook for analysis and visualization

📂 Repository Structure
ChatGPT_Reviews_Analysis/
│── data/
│   └── chatgpt_reviews.csv        # Dataset
│── notebooks/
│   └── ChatGPT_Reviews_Analysis.ipynb   # Main notebook
│── outputs/
│   ├── charts/                    # Visualizations
│   └── wordclouds/                # WordClouds
│── README.md                      # Project documentation
│── requirements.txt               # Dependencies

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/ChatGPT_Reviews_Analysis.git
cd ChatGPT_Reviews_Analysis


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook


Run the notebook:

Navigate to ChatGPT_Reviews_Analysis.ipynb

Execute the cells step by step

📢 Conclusion

This analysis of 196,000+ reviews highlights both strengths and weaknesses of ChatGPT.
By addressing accuracy, performance, and pricing concerns while continuing to enhance creativity and usability, ChatGPT can further improve customer trust and adoption.

✨ Author: Jivak Dongare
📧 Email: jivak0059@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/jivak-dongare-553315200/
