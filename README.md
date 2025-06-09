# -Market-Analysis-Report-for-National-Clothing-Chain
This project analyzes customer purchase data, product inventory, and U.S. Census income statistics to help a national clothing retailer target the right customers with the right products. Using Power BI, it applies linear regression and income prediction models to guide personalized marketing strategies. 

![Power BI](https://img.shields.io/badge/Tool-PowerBI-yellow)
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Made With](https://img.shields.io/badge/Made%20With-DAX%20%7C%20Excel%20%7C%20Power%20BI-blue)


> ✨ A data-driven marketing strategy using Power BI, census data, and customer purchasing behavior.

---

## 📌 Project Overview
This is Udacity’s third and final project under the Nanodegree Program Data Analysis and Visualization with Microsoft Power BI and focuses on advanced data analysis. (Completed on March , 2023)
An online national clothing chain is experiencing flat sales and needs insights to target lost customers. This project uses Power BI to analyze sales, customer data, product inventory, and U.S. Census data to:

- Predict customer income using regression.
- Recommend which product to advertise (Shirt, Sweater, or Leather Bag).
- Identify regions with higher-income potential.
- Understand product performance via ratings and return rates.

### Sources
US Census Bureau

Average income

location

population

industry

### Business Data

Product inventory

Product prices

Customer rating

Product return rate

### Customer Data

Customer ID

Names

Location

Date of birth

Purchase history

### Additional Data
  Weather
  
## Project Instructions
In this project, we used population statistics from the US Census Bureau to determine where the greatest income exists around the country and whether there is a correlation between sales and income. We don’t know the incomes of our customers, but we should be able to predict it by looking at their purchase history and locations and comparing that against the census data. Additionally, we want to analyze our inventory, specifically customer ratings and return rate and see if there’s a correlation between the two.

## Sources
The source material for this project can be found under the folder called “source files”.

Average Temperatures by State

Census Data

Customer List

Purchase List

State List

## ETL
Used Power Query to split the columns under the Product Inventory table using the Delimiter function. Further data transformation were needed such as changing data type, promoting header, and merging columns.

For the Purchase List table, I used Power Query’s unpivot function to unpivot the multiple-date columns as well as updating data types and renaming columns

---

## 📊 Key Visualizations

- 📍 Heatmap of household income by state  
- 📈 Scatterplot of income vs. sales with trendline and R²  
- 📊 Histogram of predicted income categories  
- 📦 Product recommendation by income group  
- 💬 Additional variable analysis (e.g., population or industry)

---

## 🔍 Analysis Questions Answered

1. What is the correlation (R²) between sales and income?  
2. What is the correlation between product ratings and return rates?  
3. What is the linear regression formula for income prediction?  
4. Which customer is likely the highest earner?  
5. Which product should be advertised the most?

---

## 🧰 Tools Used

- **Microsoft Power BI** (data modeling & visualization)
- **Excel / Google Sheets** (data review)
- **DAX** (calculated columns for regression, product assignment, and histograms)
- **Power Query (M Language)** (data cleaning and formatting)


Market Analysis with Power BI
This project analyzes customer purchase data, product inventory, and U.S. Census income statistics to help a national clothing retailer target the right customers with the right products. Using Power BI, it applies linear regression and income prediction models to guide personalized marketing strategies. Key insights are visualized through heatmaps, histograms, and scatterplots with trendlines.

The repository includes:

📊 Power BI (.pbix) file: Contains all data transformations, relationships, DAX calculations, regression analysis, and interactive visuals (cross-filtered heatmap, histogram, and scatterplot).

📝 Summary Report (.docx / .pdf): A 1–2-page executive summary outlining key insights, regression findings, R² values, and evidence-based marketing recommendations based on the visual analysis.





