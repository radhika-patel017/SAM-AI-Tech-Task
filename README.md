# SAM AI Tech Task

## SAM AI Technologies - Data Analyst Internship

This repository contains the three tasks completed for the SAM AI Technologies Data Analyst Internship.

## Dataset

Zomato Restaurant Dataset

The dataset contains information about restaurants including:
- Restaurant Name
- City
- Cuisines
- Aggregate Rating
- Votes
- Price Range

## Completed Tasks

### Task 2 - Cuisine Combination Analysis

This task identifies the most common cuisine combinations and analyzes whether certain cuisine combinations tend to have higher ratings.

Key findings:
- Chinese + North Indian is the most common cuisine combination with 616 restaurants.
- Cafe + Continental + Italian has the highest average rating among combinations represented by at least 10 rated restaurants, with an average rating of approximately 4.11.

Notebook:
`Task_2_Cuisine_Combination.ipynb`

---

### Task 3 - Data Visualization

This task uses visualizations to explore restaurant ratings, city distribution, popular cuisines, and price ranges.

Key findings:
- New Delhi has the highest number of restaurants in the dataset.
- North Indian is the most commonly available cuisine.
- Most restaurants belong to lower price ranges.
- Higher price ranges tend to have somewhat higher average ratings.

Notebook:
`Task_3_Data_Visualization.ipynb`

---

### Task 5 - Votes Analysis

This task identifies restaurants with the highest and lowest votes and analyzes the relationship between votes and restaurant ratings.

Key findings:
- Toit in Bangalore has the highest number of votes with 10,934 votes and a rating of 4.8.
- Several restaurants have 0 votes and are unrated.
- The correlation between votes and ratings is approximately 0.41, indicating a moderate positive relationship.

Notebook:
`Task_5_Votes_Analysis.ipynb`

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Repository Structure

```text
SAM-AI-Tech-Task/
│
├── README.md
├── Zomato-Dataset.csv
├── Task_2_Cuisine_Combination.ipynb
├── Task_3_Data_Visualization.ipynb
└── Task_5_Votes_Analysis.ipynb
