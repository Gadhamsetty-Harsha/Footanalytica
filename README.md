# 👟 Footanalytica - Amazon Footwear Data Analysis

## 📌 Overview
Footanalytica analyzes Amazon footwear data to uncover patterns in pricing, discounts, ratings, and brand performance. The project uses Python, web scraping, and data visualization to convert raw e-commerce data into insights for business decisions.

## 🎯 Purpose
- Understand online footwear market behavior
- Study brand performance and pricing patterns
- Analyze customer ratings and discount trends
- Support data-driven decisions for online retail
  
## 🛒 Business Problem
The online footwear market is crowded with competing brands. Retailers struggle to understand:
- What pricing attracts buyers
- How discounts influence sales
- How ratings affect brand visibility
Footanalytica solves this by collecting large-scale Amazon data and analyzing patterns that drive customer engagement.

## 🎯 Objectives
- Extract footwear data using Python and web scraping
- Clean and prepare data for accurate analysis
- Study discount trends, price variation, and rating impact
- Evaluate brand-wise performance
- Produce visual insights for decision-making

## 🧰 Tools and Libraries
- Python
- BeautifulSoup
- Requests
- Pandas
- Regular Expressions
- Matplotlib
- Seaborn

## 🕸️ Web Scraping Process
### 🔍 Data Extraction
Web scraping was used to collect:
- Brand
- Category
- Rating
- Product orders
- Discount price
- Original price
- Discount percentage
- Availability
Python libraries like BeautifulSoup and Requests parsed dynamic HTML pages to extract structured information.

## 🧹 Data Cleaning
### 🛠️ Preprocessing Steps
- Removed special symbols (₹, %, +)
- Converted text data to numeric format
- Handled null and missing values
- Removed duplicate entries
- Standardized price and discount formats
Cleaned data enabled accurate analysis and reliable visual patterns.

## 📊 Data Visualization
### 🔍 Univariate Analysis
- Top 10 brands by product count
- Price distribution
- Rating distribution
- Availability and deal keywords

### 🔗 Bivariate Analysis
- Discount vs product orders
- Price gap (original vs discount)
- Brand popularity vs discount
- Brand price comparison (box plots)

### 🔺 Multivariate Analysis
- Correlation heatmap
- Price vs rating vs orders
- Brand popularity vs discount vs orders
Visuals highlight how pricing, discounts, and ratings influence customer behavior.

## 💡 Key Insights
- Mid-range price products received more customer engagement
- High discounts did not always produce better ratings
- Several brands performed well due to balanced pricing strategies
- Price, discount, and rating values show strong relationships
- Cleaned data improved accuracy of brand comparisons

## 🧱 Challenges Faced
### 🕸️ Web Scraping Challenges
- Dynamic Amazon HTML structure
- Repeated tags and inconsistent layouts
- Missing product fields
- Maintaining accurate extraction logic

### 📉 Data Analysis Challenges
- Handling missing values
- Converting mixed data types
- Cleaning text-based numeric fields
- Standardizing inconsistent formats

## 🚀 How to Run
1. Install required libraries
   ```sh
   pip install -r requirements.txt
   ```
2. Run the scraper
   ```sh
   python scraper.py
   ```
3. Clean and analyze data
   ```sh
   python analysis.py
   ```
4. View results
Check the visuals folder for charts and insights.

## 🤝 Contributing
- Fork the repository
- Create a branch
- Commit changes
- Open a pull request
   
---
Footanalytica = Footware + Analytics 👟🛍️🏷️
