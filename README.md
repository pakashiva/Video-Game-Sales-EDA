# 🎮 Video Game Sales – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a global video game sales dataset to understand sales distribution across regions, platforms, genres, and publishers.  
A focused analysis is carried out on **Nintendo** to study its regional performance, platform presence, and yearly sales trends.

The goal of this analysis is to extract meaningful insights using statistical summaries and visualizations.

---

## 📊 Dataset Information
- **Dataset:** Video Game Sales Dataset
- **Rows:** ~16,500
- **Columns:** 11
- **Key Features:**
  - Categorical: `Name`, `Platform`, `Genre`, `Publisher`
  - Numerical: `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`, `Year`

---

## 🎯 Objectives
- Understand dataset structure and data types
- Identify and analyze missing values
- Classify numerical and categorical variables
- Analyze regional sales distribution
- Perform publisher-focused analysis (Nintendo)
- Detect and interpret outliers in sales data
- Draw business-relevant insights from the data

---

## 🔍 EDA Steps Performed

### 1️⃣ Data Understanding
- Checked dataset shape, column types, and summary statistics
- Classified columns into numerical and categorical features

---

### 2️⃣ Missing Value Analysis
- Identified missing values using `isna().sum()`
- Visualized missing vs non-missing values
- Concluded that missing values are limited and manageable

---

### 3️⃣ Sales Aggregation & Analysis
- Analyzed total sales across regions (NA, EU, JP, Other)
- Identified top genres and publishers by global sales
- Conducted a focused analysis on **Nintendo**, including:
  - Regional sales contribution
  - Platform-wise game distribution
  - Yearly global sales trends

---

### 4️⃣ Outlier Detection
- Detected outliers in regional sales using the **IQR method**
- Identified that approximately 10–15% of values are outliers
- Observed strong right-skewness due to blockbuster titles
- Outliers were **retained**, as they represent genuine high-selling games

---

### 5️⃣ Visualization
- Bar plots for regional and platform-wise analysis
- Box plots for outlier detection
- Subplots for comparative regional insights

---

## 📈 Key Insights
- North America is the largest contributor to global video game sales
- Nintendo performs strongest in North America and Japan
- Handheld platforms (DS, GBA, 3DS) dominate Nintendo’s releases
- Sales distributions are highly right-skewed due to a small number of blockbuster games
- Peak sales align with major console-generation periods

---

## ⚠️ Data Limitations
- Sales data **after 2016 is unavailable**
- Any apparent decline post-2016 reflects data unavailability rather than actual market performance

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Dataset Source
The dataset used in this project was obtained from Kaggle:

🔗 [Video Game sales Dataset - Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)

---

## 👤 Author
**Shiva Prasad**  
Aspiring Data Analyst / Data Scientist  

---

⭐ If you find this project useful, feel free to star the repository!
