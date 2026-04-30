# Association Rule Mining – Mushroom Dataset

## Project Overview
This project applies association rule mining techniques to analyze the Mushroom dataset and identify patterns that distinguish edible and poisonous mushrooms.

The dataset contains 8,124 instances with categorical features describing mushroom characteristics such as odor, color, and shape. :contentReference[oaicite:0]{index=0}

## Tools Used
- Python
- Pandas
- Apriori Algorithm

## Dataset
- Mushroom Dataset (UCI / OpenML)
- 8,124 instances
- 22 features + class label (edible / poisonous) :contentReference[oaicite:1]{index=1}

## What I Did
- Preprocessed the dataset (handling missing values and encoding)
- Converted categorical data into a transaction matrix
- Applied One-Hot Encoding for association rule mining
- Implemented the Apriori algorithm
- Generated frequent itemsets and association rules

## Data Preprocessing
- Handled missing values by treating them as a separate category instead of removing them :contentReference[oaicite:2]{index=2}  
- Removed non-informative features (e.g., constant columns) :contentReference[oaicite:3]{index=3}  
- Converted dataset into binary transaction format (118 features after encoding) :contentReference[oaicite:4]{index=4}  

## Data Mining Methodology
- Algorithm: Apriori
- Minimum Support: 0.20
- Confidence Threshold: 0.80 :contentReference[oaicite:5]{index=5}  

## Results
- 376 frequent itemsets  
- 208 association rules  
- 9 rules predicting mushroom class :contentReference[oaicite:6]{index=6}  

### Key Findings
- Odor is the strongest indicator of mushroom toxicity  
- Mushrooms with foul odor are always poisonous  
- Mushrooms with no odor are highly likely edible :contentReference[oaicite:7]{index=7}  

## Learning Outcomes
- Understanding association rule mining techniques  
- Importance of data preprocessing  
- Extracting meaningful patterns from categorical data  
- Applying Apriori algorithm in real-world datasets  

## 📄 Project Report
👉 [View Full Report](Data Mining Project.pdf)
