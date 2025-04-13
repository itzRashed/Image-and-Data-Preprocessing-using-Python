# 🧹 Amazon Food Reviews – Data Cleaning
This project demonstrates basic **data exploration** and **cleaning techniques** applied to an **Amazon Food Reviews** dataset.  
It showcases how to handle missing values, detect duplicates, and perform simple visualizations — all fundamental steps in **data preprocessing**.

> 📍 Implemented in **Python** using **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib**

## 📌 **Project Overview**
The main goal of this project is to prepare a large dataset of food reviews from Amazon for further analysis by:
- Cleaning irrelevant or redundant columns  
- Handling missing and duplicate values  
- Renaming columns for clarity  
- Visualizing data distributions

## 🗃️ **Dataset**
📂 **File Used:** `Reviews.csv`  
📄 Contains user-generated food product reviews from Amazon, with fields like:
- `UserId`, `ProductId`, `ProfileName`, `Score`, `Time`, `Summary`, `Text`

🔍 Sampled 10% of the original dataset for quicker processing.

## ⚙️ **Code Functionality**

### 🔍 **Data Loading & Sampling**
- Loaded full dataset into a DataFrame  
- Took a **10% random sample** (`frac=0.1`) for efficient analysis  

### 📐 **Data Overview**
- Checked dataset shape  
- Previewed first 10 rows  
- Displayed descriptive statistics of numeric columns  

### 🧹 **Data Cleaning**
- Dropped irrelevant columns: `ProductId`, `Score`  
- Renamed `UserId` ➝ `User_Id`  
- Checked for missing values using `isna().sum()`  
- Identified full and partial duplicates using:
  - `df.duplicated()`  
  - `df.duplicated(subset=['ProductId'])`  
- Queried specific values for in-depth checks  

### 📊 **Data Visualization**
- **Bar plot**: Frequency of different review `Score` values  
- **Histogram**: Distribution of scores

## 🛠️ **Requirements**
Install necessary libraries:
```bash
pip install pandas numpy matplotlib seaborn

🚀 Usage
- Clone the repository
- Place Reviews.csv in the working directory or update the file path
- Run the Python script or open in a Jupyter/Colab notebook
- Review outputs for data insights and visualizations

🧠 What I Learned
- Handling large datasets by sampling
- Detecting and removing duplicate and null data
- Basic visual analytics using Seaborn and Matplotlib
- Importance of clean and well-structured data before analysis or modeling

📜 License
This project is licensed under the MIT License – free to use, share, and modify.
