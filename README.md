🎮 Video Game Sales – Exploratory Data Analysis (EDA)
📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a video game sales dataset to understand sales distribution, regional trends, platform presence, publisher dominance, and outlier behavior.
A focused analysis is also carried out on Nintendo to study its regional performance, platform strategy, and yearly sales trends.

📊 Dataset Information
Rows: ~16,500
Columns: 11
Target Variables: Regional and Global Sales
Key Columns:
Categorical: Name, Platform, Genre, Publisher
Numerical: NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales, Year

🎯 Objectives
Understand dataset structure and data types
Identify and analyze missing values
Classify numerical and categorical features
Perform regional and publisher-based sales analysis
Analyze Nintendo’s sales across regions, platforms, and years
Detect and interpret outliers in sales data
Draw meaningful business insights from the data

🔍 EDA Steps Performed

1️⃣ Data Understanding
Checked dataset shape, column types, and basic statistics
Classified columns into numerical and categorical

2️⃣ Missing Value Analysis
Identified missing values using isna().sum()
Visualized missing vs non-missing values
Concluded that missing values are minimal and manageable

3️⃣ Sales Aggregation & Insights
Analyzed total sales by region
Identified top genres and publishers
Focused analysis on Nintendo, including:
Regional sales distribution
Platform-wise game count
Yearly global sales trends

4️⃣ Outlier Detection
Used the IQR (Interquartile Range) method
Detected outliers in:
NA_Sales
EU_Sales
JP_Sales
Other_Sales
Found that ~10–15% of values are outliers due to right-skewed distributions
Outliers were retained, as they represent genuine blockbuster titles

5️⃣ Visualization
Boxplots for numerical features
Bar charts for regional and platform analysis
Subplots for comparative regional insights

📈 Key Insights
North America is the largest contributor to global video game sales
Nintendo’s strongest markets are North America and Japan
Handheld platforms (DS, GBA, 3DS) dominate Nintendo’s releases
Sales distributions are highly right-skewed due to blockbuster games
Sales peaks align with major console generations (2005–2009)

⚠️ Data Limitations
Sales data post-2016 is unavailable
Any observed decline after 2016 reflects data unavailability, not actual market performance

🛠️ Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

🚀 Future Scope
Feature engineering (e.g., decade-based analysis)
Comparative publisher analysis (Nintendo vs Sony vs EA)
Predictive modeling on sales trends
Interactive dashboards

👤 Author
Shiva Prasad
Aspiring Data Analyst / Data Scientist
