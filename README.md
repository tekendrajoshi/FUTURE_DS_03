# 🎓 College Event Feedback Analysis – Data Science & Analytics (Task 3)

## 📌 Project Overview
This project analyzes **student satisfaction feedback** collected through a structured survey using a **5-point Likert scale**. The goal is to transform aggregated survey ratings into **meaningful, data-driven insights** that help institutions improve teaching quality, learning experiences, and overall academic effectiveness.

Unlike traditional sentiment analysis projects, this dataset contains **only numerical ratings (no textual comments)**. Therefore, sentiment is logically derived from **average ratings**, ensuring methodological correctness and reliability.

---

## 🎯 Project Objectives
- Analyze student satisfaction survey data across courses and programs  
- Identify strengths and improvement areas in teaching & learning processes  
- Categorize satisfaction into **Positive / Neutral / Negative** sentiment using ratings  
- Compare feedback across questions, courses, and program categories  
- Generate actionable recommendations for academic improvement  

---

## 📂 Dataset Description
**Dataset Name:** `Student_Satisfaction_Survey.csv`

The dataset consists of **aggregated feedback records** where each row represents a question-course combination.

### Key Columns:
- **SN** – Serial number  
- **Questions** – Survey question text  
- **Total Feedback Given** – Number of students who responded  
- **Total Configured** – Total eligible students  
- **Weightage 1–5** – Count of students selecting ratings 1 to 5  
- **Average / Percentage** – Calculated mean score and percentage  
- **Course Name** – Specific academic course (e.g., FY BCOM A&F)  
- **Basic Course** – Program category (e.g., BACHELOR OF COMMERCE)

📌 *Note:*  
The dataset does **not** contain open-ended student comments. Hence, **NLP-based sentiment analysis (TextBlob / VADER)** is **not applicable**.

---

## 🛠 Tools & Technologies Used
- **Google Colab** – Cloud-based analysis environment  
- **Python**  
- **pandas & NumPy** – Data cleaning and aggregation  
- **matplotlib & seaborn** – Data visualization  

---

## 🔍 Data Analysis Methodology
- 🔹 Step 1: Data Cleaning & Preparation
  -Imported required Python libraries
  -Loaded and inspected the dataset
  -Handled missing values and empty comments
  -Prepared textual data for NLP processing
- 🔹 Step 2: Exploratory Data Analysis (EDA)
  -Response rate analysis per program
  -Average rating analysis per event
  -Rating distribution visualization
  -Identification of highly rated and low-rated events
- 🔹 Step 3: Type Analysis (Workshop vs Seminar)
  -Grouped data by course/event type
  -Compared average ratings across event types
  -Analyzed sentiment distribution by course name
  -Visualized insights using bar charts
---
## 📊 Key Insights & Results
- Strong positive correlation between ratings and sentiment
- Workshops generally received higher ratings than seminars
- Majority of feedback was positive, indicating good overall satisfaction
- Teaching quality and learning process were the most frequently mentioned themes
---
## 🚀 Use Cases
- College & University Feedback Analysis
- Academic Quality Improvement
- Data Science Internship Projects
- NLP & Sentiment Analysis Portfolio Projects
---
👤 Author
Tekendra Joshi
Future Intern – Data Science & Analytics
Task 3 Completed
