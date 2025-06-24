# Skill-Based Job Recommender using NLP

This project recommends relevant jobs based on the user's input skills. It uses TF-IDF vectorization and cosine similarity to match user skills with job descriptions from a dataset.

## Features
- User enters skills (e.g., Python, SQL)
- System returns top 5 matching jobs
- Each match includes job title, similarity score, and description preview

## Dataset
File: `resume_jobs_large.csv`  
Contains job titles and job descriptions.

## Libraries Used
- pandas
- scikit-learn

## How to Run
1. Install required libraries:
pip install -r requirements.txt
