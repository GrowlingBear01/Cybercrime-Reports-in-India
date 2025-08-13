# Cybercrime-Reports-in-India
Exploratory Data Analysis of Cybercrime in India
An analysis of cybercrime patterns across various cities and states in India, focusing on the motives behind the crimes.

📋 Table of Contents
Overview

Dataset

Analysis and Key Findings

Region-wise Crime Analysis

Crime Type (Motive) Analysis

Visualizations

Tools and Technologies

How to Run This Project

📖 Overview
This project performs an Exploratory Data Analysis (EDA) on a dataset of cybercrime cases reported in India. The primary goal is to uncover key patterns and insights related to the geographical distribution of cybercrimes and the primary motives driving them. By visualizing this data, we can better understand the landscape of cybercrime in the country.

💾 Dataset
The dataset used for this analysis is Dataset_CyberCrime_Sean.csv, sourced from Kaggle.

Source: Dataset CyberCrime in India on Kaggle

Structure: The dataset contains records of cybercrime cases for various cities and states in India. The columns are broken down by the motive behind the crime (e.g., Fraud, Extortion, Personal Revenge).

Limitations: It's important to note that this dataset does not contain temporal data (year of the crime) or demographic information (age/gender of victims/perpetrators). Therefore, trend analysis over time is not possible with this specific dataset.

📊 Analysis and Key Findings
We focused on answering two primary questions:

Region-wise Crime Analysis
Question: Which states and cities report the highest number of cybercrime cases?

Finding: After normalizing for summary rows, Karnataka and Uttar Pradesh emerge as the states with the highest volume of cybercrime cases. Major metropolitan areas like Mumbai and Bengaluru are also significant hotspots.

Crime Type (Motive) Analysis
Question: What are the most common motives behind the reported cybercrimes?

Finding: Fraud is overwhelmingly the most dominant motive, accounting for a vast majority of the cases. Other significant motives include Sexual Exploitation, Extortion, and Causing Disrepute.

📈 Visualizations
Two primary visualizations were generated to summarize the findings:

Top 15 Regions by Total Cybercrime Cases: A horizontal bar chart showing the states and cities with the most reported cases.

Total Cybercrime Cases by Motive: A bar chart illustrating the prevalence of different cybercrime motives.

🛠️ Tools and Technologies
This analysis was conducted using Python in a Jupyter Notebook environment. The key libraries used are:

Pandas: For data manipulation and cleaning.

Matplotlib: For creating the plots.

Seaborn: For enhancing the visual aesthetics of the plots.
