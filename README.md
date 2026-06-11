# 🍽️ Restaurant Recommendation System
## 📌 Project Overview
This project implements a Restaurant Recommendation System using a Content-Based Filtering approach. 
The system recommends restaurants based on user preferences such as cuisine type, city, and price range.
The application provides personalized restaurant suggestions through an interactive Streamlit interface, 
helping users discover restaurants that match their interests.
---
## 🎯 Objective
To build a restaurant recommendation system that suggests restaurants based on user preferences and restaurant characteristics.
---
## 📂 Dataset
The dataset contains restaurant information including:
* Restaurant Name
* City
* Cuisines
* Average Cost for Two
* Price Range
* Aggregate Rating
* Votes
* Online Delivery Availability
* Table Booking Availability

### Dataset Size
* Total Records: 9,551
* Total Features: 21
---

## 🛠️ Project Workflow
### 1. Data Preprocessing
* Loaded the dataset using Pandas.
* Handled missing values in important columns.
* Encoded categorical variables for processing.

### 2. Recommendation Criteria
The recommendation system considers:
* Cuisine Preference
* City Selection
* Price Range
### 3. Content-Based Filtering
Restaurants are filtered based on user preferences and ranked using:
* Aggregate Rating
* Number of Votes
### 4. Recommendation Generation
The system displays the most relevant restaurants that match the user's criteria.
---

## 💻 Technologies Used
* Python
* Pandas
* Streamlit
* Scikit-Learn
---

## 🚀 Features
✅ Interactive User Interface
✅ Restaurant Recommendations Based on:
* Preferred Cuisine
* City
* Budget (Price Range)
✅ Top-Rated Restaurant Suggestions
✅ Fast and User-Friendly Experience
---

## 📊 Sample Recommendation Process
1. User selects a city.
2. User enters a preferred cuisine.
3. User selects a price range.
4. System filters matching restaurants.
5. Restaurants are ranked by rating and votes.
6. Top recommendations are displayed.
---

## ▶️ How to Run
### Install Dependencies
```bash
pip install pandas streamlit scikit-learn
```
### Run the Application
```bash
streamlit run app.py
```
### Open in Browser
```text
http://localhost:8501
```
---
## 📈 Results
The recommendation system successfully provides personalized restaurant suggestions based on user preferences.
The quality of recommendations is improved by considering:
* Restaurant Ratings
* Customer Votes
* Cuisine Similarity
* Price Range Matching
---
## 🎓 Learning Outcomes
Through this project, I gained hands-on experience in:
* Data Preprocessing
* Recommendation Systems
* Content-Based Filtering
* User Preference Analysis
* Streamlit Application Development
* Machine Learning Concepts
---
## 👨‍💻 Author
Pavan Kedika
Machine Learning Internship Project
