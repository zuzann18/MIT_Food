# MIT_Food
**Report Title: FoodHub Order Data Analysis**

**Project and Course Name:** Foundations of Data Science

**Date:** [Insert Date]

---

## **Executive Summary**

### **Key Findings:**
- **Peak Order Times:** Orders are more frequent on weekends.
- **Cuisine Popularity:** American, Japanese, and Mexican cuisines have the highest demand.
- **Order Cost Trends:** The average order cost is around **$20-$30**.
- **Delivery & Preparation Times:**
  - Average **food preparation time**: ~25 minutes.
  - Average **delivery time**: ~22 minutes.
- **Ratings Distribution:** Some ratings are missing (marked as "Not given"). Orders with higher costs tend to have better ratings.

### **Recommendations:**
- **Optimize Weekend Deliveries:** Increase delivery resources on weekends.
- **Improve Preparation Time:** Identify slow restaurants to enhance efficiency.
- **Encourage Customer Reviews:** Reduce missing ratings by prompting feedback.

---

## **Business Problem Overview and Solution Approach**

### **Problem Statement:**
The objective is to analyze FoodHub’s order dataset to gain insights into restaurant demand, customer preferences, and delivery efficiency.

### **Solution Approach:**
- **Exploratory Data Analysis (EDA):** Understand trends in customer behavior.
- **Univariate Analysis:** Study distribution of individual variables.
- **Multivariate Analysis:** Identify correlations between key metrics.
- **Actionable Insights:** Provide recommendations based on findings.

---

## **Data Overview**

### **Dataset Structure:**
- **Total Entries:** 1,898 orders
- **Columns:**
  - Order & Customer IDs
  - Restaurant Name & Cuisine Type
  - Cost of Order
  - Day of the Week (Weekday/Weekend)
  - Customer Rating
  - Food Preparation Time & Delivery Time

### **Data Quality Observations:**
- **Ratings:** Some missing values ("Not given").
- **Time Variables:** No missing values, but some high delivery times observed.

---

## **Univariate Analysis**

### **Order Cost Distribution:**
- Most orders cost between **$10-$40**.
- Few high-value orders exceed **$50**.

### **Ratings Analysis:**
- Ratings range from **1 to 5**, but some are missing.
- Higher-cost orders tend to have **better ratings**.

### **Delivery Time:**
- Average: **22 minutes**.
- Some extreme values exceed **45 minutes**, indicating delays.

---

## **Multivariate Analysis**

### **Correlation Analysis:**
- **Cost vs. Rating:** Higher-cost orders generally receive better ratings.
- **Delivery Time vs. Order Cost:** No strong correlation, suggesting delivery delays are not price-dependent.
- **Preparation Time vs. Delivery Time:** Some restaurants have consistently higher wait times.

### **Key Observations:**
- **Weekend orders** are more frequent but do not have significantly longer delivery times.
- Certain restaurants have higher delays; further investigation is needed.

---

## **Conclusions and Recommendations**

- **Optimize weekend delivery staffing** to handle peak order volumes.
- **Identify slow-performing restaurants** and streamline food preparation.
- **Improve rating collection** by encouraging more customer reviews.
- **Monitor high-delivery-time restaurants** for potential inefficiencies.

These insights will help FoodHub enhance customer satisfaction and operational efficiency.

