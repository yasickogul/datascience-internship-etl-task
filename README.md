# Data Science Internship Task – ETL & Data Analysis on Social Network Ads Dataset

This repository contains a simple **ETL (Extract, Transform, Load)** pipeline and **data analysis** for a dataset related to social network advertisements. The task was completed as part of a data science internship assignment.

---

## 📁 Repository Structure

- `social_ads.csv`: Original raw dataset
- `cleaned_social_network_ads.csv`: Cleaned and transformed dataset
- `etl_analysis_social_ads.ipynb`: Google Colab notebook containing the full ETL process and analysis

---

## 📌 Project Overview

The objective of this task was to:

1. Understand the structure of the dataset
2. Design and implement an ETL pipeline
3. Generate meaningful insights using Python and data visualization
4. Document and present the findings

---

## 📊 Dataset Description

The dataset contains the following features:

- `Age`: Age of the individual
- `EstimatedSalary`: Estimated annual income
- `Purchased`: Whether the person purchased the product (1 = Yes, 0 = No)

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 🔄 ETL Pipeline Summary

- **Extract**: Loaded the dataset directly from GitHub using:
  ```python
  url = "https://raw.githubusercontent.com/yasickogul/datascience-internship-etl-task/main/social_ads.csv"
  df = pd.read_csv(url)

📈 Insights from the Analysis
Most users did not purchase the product.

Purchasers are generally older (30–60) and have higher salaries (60K+).

A clear cluster of likely purchasers exists in the 35+ age and higher income range.

Younger users, regardless of income, are less likely to make a purchase.

# 🚀 How to Run
## 🧾 Steps:
1.Open your browser and go to Google Colab

2.Click on "File" > "Open notebook"

3.Select the "GitHub" tab

4.In the search bar, paste the following GitHub repository URL: https://github.com/yasickogul/datascience-internship-etl-task
5.You’ll see a list of notebooks from the repo. Click on: etl_analysis_social_ads.ipynb
6.Once the notebook opens, run each cell by clicking the "play" button (▶️) or using Shift + Enter
7.Run the notebook cells one by one using the play button (▶️) on the left of each cell.

The dataset is automatically loaded from GitHub using this code at the top of the notebook:
url = "https://raw.githubusercontent.com/yasickogul/datascience-internship-etl-task/main/social_ads.csv"


The notebook includes:
Data loading and summar
ETL steps (extracting, cleaning, saving)
Visualizations and insights

No setup or installation is needed — just a browser and an internet connection.


📬 Contact
For questions or collaboration:
### Yasickogul Athiyan
[LinkedIn](http://www.linkedin.com/in/yasickogul-athiyan-617a2024a)


