# Hypothesis Testing Project for Jeopardy Questions Using Python and Pandas 🎯  

## 📌 Project Overview

This project focuses on the **cleaning, exploration, and analysis** of Jeopardy game show questions using Python and pandas. 
It serves as a practical example of **data wrangling** techniques applied to real-world unstructured text data.

The goal is to answer questions such as:
- What are the most common question topics in Jeopardy?
- Is there a relationship between the difficulty of a question and its monetary value?
- Are certain categories more frequently featured in higher-value questions?

---

## 📁 Dataset

The project uses a dataset containing past Jeopardy questions with fields like:
- `Show Number`
- `Air Date`
- `Round`
- `Category`
- `Value`
- `Question`
- `Answer`

File formats included:
- `JEOPARDY_CSV.csv`
- `JEOPARDY_QUESTIONS1.json`

---

## 🧹 Data Cleaning Steps

- Converted monetary `Value` fields to numeric values
- Removed punctuation and normalized text case
- Filtered duplicates and irrelevant rows
- Converted `Air Date` to datetime format

---

## 🔍 Analysis Highlights

- Identified high-frequency categories and keywords
- Analyzed trends over time in question value and difficulty
- Explored correlations between question structure and success

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

---

## ▶️ How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/meryemcamci/jeopardy-questions-project.git
   cd jeopardy-questions-project
