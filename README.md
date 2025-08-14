# python_analyst_pandas_pro
Hi i am saket dhaka . i made this project to master pandas in python as a analyst . i covered industry asked questions and also provided the dataset.
Python Pandas Data Analysis – Cricket Dataset 🏏
📌 Project Overview

This project demonstrates data analysis using Python’s Pandas library on a cricket dataset. It covers:

Data importing

Data exploration

Data cleaning

Data manipulation

Basic analytics

It’s aimed at helping beginners understand pandas workflows in a clear and practical way.

📂 Dataset

The dataset used is cricket_new.csv, containing cricket match/player statistics.
It is imported into the environment using:

from google.colab import files
files.upload()


and loaded into Pandas using:

import pandas as pd
df = pd.read_csv('cricket_new.csv')

🛠️ Tools & Libraries Used

Python 3

Pandas – Data analysis and manipulation

NumPy – Numerical computations

Google Colab – Running the notebook

🔍 Key Operations Performed

Importing Libraries & Dataset

Viewing Data – df.head(), df.info(), df.describe()

Data Cleaning – Handling missing values, renaming columns

Filtering & Selecting Data – loc[], iloc[], conditional filters

Sorting & Grouping – sort_values(), groupby()

Statistical Analysis – Mean, median, sum, min/max

Exporting Data – Saving processed data to CSV
