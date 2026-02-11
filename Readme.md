# Airbnb Open Data Analysis

📊 Exploratory Data Analysis (EDA) | Data Cleaning | Visualization | Business Insights

---

## 📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on Airbnb Open Data to uncover pricing trends, neighborhood patterns, host behavior, availability trends, and review dynamics.

The objective was to clean the dataset, analyze key features, and derive actionable business insights related to pricing strategies, location performance, and host characteristics.

---

## 📊 Dataset Description

The dataset contains Airbnb listings information including:

- Neighbourhood group
- Neighbourhood
- Room type
- Price
- Review ratings
- Reviews per month
- Availability (365 days)
- Host verification status
- Host listing counts
- Service fee
- Construction year
- Number of reviews

Total listings analyzed: ~100,000+

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Dropped `license` column due to excessive missing values
- Identified and removed duplicate records
- Standardized inconsistent categorical values:
  - Corrected spelling errors in neighbourhood groups (e.g., "brookln" → "Brooklyn")
- Checked and analyzed missing values
- Identified categorical and numerical columns separately

---

## 🔍 Exploratory Data Analysis (EDA)

### 📍 Location-Based Analysis
- Listings distribution by neighbourhood group
- Average price by neighbourhood group
- Most popular neighbourhood by listing count

### 🏠 Room Type Analysis
- Listings distribution by room type
- Average price by room type
- Average rating by room type
- Price distribution comparison across room types

### 💰 Pricing Analysis
- Mean, median, min, max price
- Price distribution (histograms + boxplots)
- Price vs number of reviews
- Price vs reviews per month
- Price vs service fee
- Effect of review rating on price (violin plot)
- Effect of host verification on price

### 📈 Review & Engagement Analysis
- Listings with highest number of reviews
- Average reviews per month
- Availability trends
- Listings available 365 days

### 👤 Host Analysis
- Verified vs non-verified hosts
- Top hosts by number of listings
- Host listing count distribution

### 🏗 Construction Trends
- Room construction trends over years (line plot)

### 🔗 Correlation Analysis
- Correlation heatmap for numerical features
- Identified relationships between pricing and other variables

---

## 📊 Visualizations Used

- Histograms
- Boxplots
- Count plots
- Scatter plots
- Violin plots
- Bar charts
- Line plots
- Correlation heatmap

All visualizations were created using:
- Matplotlib
- Seaborn

---

## 🔑 Key Insights

- Manhattan and Brooklyn dominate listing counts.
- Entire homes tend to have higher prices compared to private/shared rooms.
- Higher review counts do not necessarily correspond to higher prices.
- Host verification has limited direct impact on pricing.
- Service fee is positively correlated with price.
- Certain neighbourhood groups consistently show higher pricing trends.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---



## 🚀 Conclusion

This project demonstrates:

- Data cleaning and preprocessing skills
- Structured exploratory data analysis
- Statistical interpretation
- Data visualization for business storytelling
- Insight extraction from large real-world datasets

The analysis provides practical insights that could assist Airbnb hosts and business strategists in optimizing pricing and listing strategies.

---

## 👤 Author

Swaroop Sandanshive
