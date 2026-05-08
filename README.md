# SmartCart Customer Segmentation using Unsupervised Machine Learning

## Project Overview

This project focuses on **Customer Segmentation** using **Unsupervised Machine Learning** techniques. The dataset contains customer information such as income, spending habits, education, marital status, and purchase behavior.

The main goal of this project is to group customers into different clusters based on their behavior and characteristics. These clusters can help businesses understand customer patterns and improve marketing strategies.

This project was developed using:

* Python
* Anaconda
* JupyterLab Notebook
* Machine Learning Libraries from Scikit-learn

---

# Features of the Project

## Data Preprocessing

* Handling missing values
* Feature engineering
* Removing unnecessary columns
* Outlier detection and removal
* Encoding categorical variables
* Feature scaling

## Exploratory Data Analysis (EDA)

* Correlation Heatmap
* Data Visualization
* PCA Visualization

## Machine Learning Techniques Used

### 1. K-Means Clustering

Used to divide customers into different clusters.

### 2. Agglomerative Clustering

Hierarchical clustering technique used for customer grouping.

### 3. PCA (Principal Component Analysis)

Used for dimensionality reduction and visualization.

### 4. Silhouette Score

Used to evaluate clustering performance.

### 5. Elbow Method

Used to find the optimal number of clusters.

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* JupyterLab
* Anaconda

---

# Dataset Information

Dataset File:

```bash
smartcart_customers.csv
```

The dataset contains customer details such as:

* Income
* Age
* Spending
* Education
* Marital Status
* Purchase Data
* Children Information
* Campaign Response

---

# Project Structure

```bash
SmartCart-Customer-Segmentation/
│
├── smartcart.ipynb
├── smartcart_customers.csv
├── README.md
└── requirements.txt
```

---

# Installation and Setup

## Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/SmartCart-Customer-Segmentation.git
```

## Step 2: Open Project Folder

```bash
cd SmartCart-Customer-Segmentation
```

## Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

## Step 4: Run Jupyter Notebook

```bash
jupyter lab
```

---

# Required Libraries

Create a `requirements.txt` file and add:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyterlab
kneed
```

---

# Machine Learning Workflow

## 1. Data Cleaning

* Missing values handled using median values.
* Unnecessary columns removed.

## 2. Feature Engineering

Created new features such as:

* Age
* Total Spending
* Total Children

## 3. Encoding

Categorical data converted into numerical form using OneHotEncoder.

## 4. Scaling

Data normalized using StandardScaler.

## 5. PCA

Reduced dimensions for visualization.

## 6. Clustering

Applied:

* K-Means Clustering
* Agglomerative Clustering

## 7. Evaluation

Used:

* Elbow Method
* Silhouette Score

---

# Results

The model successfully segmented customers into multiple clusters based on purchasing behavior and demographics.

These insights can help businesses:

* Target customers effectively
* Improve marketing campaigns
* Increase customer engagement
* Understand customer behavior

---

# Future Improvements

* Deploy project using Streamlit or Flask
* Add interactive dashboard
* Use DBSCAN clustering
* Improve cluster visualization
* Perform advanced customer analytics

---

# Author

Parul Gupta
B.Tech Student
Machine Learning & Data Science Enthusiast

---

# How to Push This Project to GitHub

## Step 1: Create GitHub Account

Go to:

[https://github.com](https://github.com)

Sign up if you do not already have an account.

---

## Step 2: Create a New Repository

1. Click on **New Repository**
2. Repository Name:

```bash
SmartCart-Customer-Segmentation
```

3. Select:

* Public
* Add README later (optional)

4. Click **Create Repository**

---

## Step 3: Install Git

Download Git from:

[https://git-scm.com/](https://git-scm.com/)

Install it on your laptop.

---

## Step 4: Open Anaconda Prompt

Go to:

```bash
Start Menu → Anaconda Prompt
```

---

## Step 5: Move to Your Project Folder

Example:

```bash
cd Desktop
cd SmartCart-Customer-Segmentation
```

---

## Step 6: Initialize Git

```bash
git init
```

---

## Step 7: Add Files

```bash
git add .
```

---

## Step 8: Commit Files

```bash
git commit -m "Initial commit"
```

---

## Step 9: Connect GitHub Repository

Replace `your-username` with your GitHub username.

```bash
git remote add origin https://github.com/your-username/SmartCart-Customer-Segmentation.git
```

---

## Step 10: Push Code to GitHub

```bash
git branch -M main
git push -u origin main
```

---

# How to Upload Jupyter Notebook Properly

Make sure these files are present:

* smartcart.ipynb
* smartcart_customers.csv
* README.md
* requirements.txt

Then push all files together using:

```bash
git add .
git commit -m "Added notebook and dataset"
git push
```

---

# Useful Git Commands

## Check Status

```bash
git status
```

## Add New Changes

```bash
git add .
```

## Commit Changes

```bash
git commit -m "Updated project"
```

## Push Changes

```bash
git push
```

---

# Output

After pushing successfully, your project will appear on GitHub and you can share the repository link in:

* Resume
* LinkedIn
* Internship Applications
* College Projects

---

# License

This project is for educational and learning purposes.
