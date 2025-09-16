🎓 College Event Feedback Analysis
📌 Overview

This project, part of the Future Interns program, focuses on analyzing student feedback from college courses and events to derive actionable insights and improve campus life.

The analysis combines quantitative ratings (1–5 scale) with qualitative text sentiment (optional comments) to evaluate student satisfaction and highlight areas for improvement.

🛠 Tech Stack

Google Colab → Online notebook (no setup required)

pandas → Data cleaning & preparation

matplotlib / seaborn → Data visualization

NLTK (VADER) → Sentiment analysis of comments

📂 Dataset

The dataset comes from a Google Forms export containing student ratings across multiple aspects:

Well versed with the subject

Explains concepts clearly

Use of presentations

Difficulty of assignments

Solves doubts willingly

Structuring of the course

Provides support beyond syllabus

Course recommendation relevance

Overall Score

👉 An additional Comments column was added (simulated) to demonstrate text sentiment analysis.

🚀 Project Workflow

Data Preparation

Load CSV in Colab

Clean column names & handle missing values

Descriptive Statistics

Mean, median, and distribution of ratings

Visualizations

📊 Bar charts → Average rating per question

🥧 Pie chart → Distribution of overall satisfaction

🔥 Heatmap → Correlation between survey questions

Sentiment Analysis (Optional)

VADER applied to text comments

Sentiment categories: Positive, Neutral, Negative

Sentiment distribution visualized

Insights & Recommendations

Strengths: e.g., “Solves doubts willingly” rated highest

Weaknesses: “Difficulty of assignments” rated lowest

Recommendations: simplify assignments, more practice sessions, continue strong presentation usage

📊 Example Outputs

Bar Chart – Average ratings across feedback aspects

Pie Chart – Overall satisfaction distribution

Heatmap – Correlation between feedback items

Count Plot – Sentiment distribution from comments

📁 Repository Contents

notebooks/College_Event_Feedback_Analysis.ipynb → Main Google Colab notebook

data/student_feedback.csv → Raw dataset

data/student_feedback_analyzed.csv → Processed dataset

README.md → Project documentation

🧠 Skills Demonstrated

Data wrangling & cleaning with pandas

Visual storytelling with matplotlib / seaborn

Correlation & survey analysis

NLP-based sentiment scoring with VADER

Communicating actionable insights

🚀 How to Run

Clone this repository:

git clone https://github.com/<your-username>/college-event-feedback-analysis.git


Open the notebook in Google Colab or Jupyter.

Upload the dataset (student_feedback.csv).

Run all cells to reproduce the analysis and charts.
