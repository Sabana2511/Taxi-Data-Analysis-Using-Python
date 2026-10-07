# 🚕 Taxi Data Analysis Using Python

## 📌 Project Overview

This project analyzes taxi trip data using **Python, Pandas, Matplotlib, and Seaborn**. The analysis focuses on data cleaning, missing-value handling, exploratory data analysis, and visualization to identify patterns in taxi fares, trip distances, payment methods, pickup locations, and customer behavior.

The project uses the built-in **Taxis dataset from Seaborn** and was developed using **Google Colab**.

---

## 🎯 Objectives

* Load and explore the Taxi dataset
* Identify and handle missing values
* Convert timestamp data into the appropriate datetime format
* Analyze taxi fares and trip distances
* Understand customer payment preferences
* Analyze taxi trip distribution across pickup boroughs
* Identify relationships between distance, fare, tips, tolls, and total amount
* Create meaningful visualizations

---

## 🛠️ Technologies Used

| Technology   | Purpose                        |
| ------------ | ------------------------------ |
| Python       | Data analysis and programming  |
| Pandas       | Data manipulation and cleaning |
| NumPy        | Numerical operations           |
| Matplotlib   | Data visualization             |
| Seaborn      | Statistical visualization      |
| Google Colab | Development environment        |

---

## 📂 Dataset

The project uses the **`taxis` dataset** available through Seaborn.

### Important Features

* `pickup` – Pickup date and time
* `dropoff` – Drop-off date and time
* `passengers` – Number of passengers
* `distance` – Trip distance
* `fare` – Taxi fare
* `tip` – Tip amount
* `tolls` – Toll charges
* `total` – Total trip amount
* `payment` – Payment method
* `pickup_zone` – Pickup zone
* `dropoff_zone` – Drop-off zone
* `pickup_borough` – Pickup borough
* `dropoff_borough` – Drop-off borough

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

* Checked the dataset for missing values
* Identified columns containing missing data
* Used median imputation for numerical variables where appropriate
* Used mode imputation for categorical variables
* Removed rows with missing values in critical fields when necessary
* Converted the `pickup` column into datetime format
* Sorted the dataset based on pickup time

---


# 📈 Data Analysis & Visualization

The project includes the following visualizations:

### 1. Line Chart

**Fare Over Time**

Used to understand how taxi fare values vary across pickup times.

### 2. Bar Chart

**Total Fare by Pickup Borough**

Used to compare fare revenue across different pickup boroughs.

### 3. Pie Chart

**Payment Method Distribution**

Used to understand customer payment preferences.

### 4. Histogram

**Taxi Trip Distance Distribution**

Used to analyze the distribution of short- and long-distance taxi trips.

### 5. Box Plot

**Tips by Pickup Borough**

Used to compare customer tipping behavior across different boroughs.

### 6. Count Plot

**Trips by Pickup Borough**

Used to identify locations with higher taxi demand.

### 7. Scatter Plot

**Distance vs Fare**

Used to understand the relationship between trip distance and fare.

### 8. Correlation Heatmap

Analyzes relationships between:

* Distance
* Fare
* Tip
* Tolls
* Total

### 9. Pair Plot

Examines relationships between:

* Distance
* Fare
* Tip
* Total

with pickup zones.

### 10. Violin Plot

**Fare by Payment Method**

Used to compare fare distributions across different payment methods.

---

# 💼 Business Insights

## 1. Dataset Volume

After data cleaning and validation, the final dataset contained **6,433 taxi trips across 14 variables**.

This provides a reliable dataset for analyzing:

* Taxi demand
* Fare behavior
* Trip distance
* Customer tips
* Payment preferences

---

## 2. Data Quality Improvement

Missing values were initially identified in **5 categorical columns**:

* Payment – **44 records**
* Pickup Zone – **26 records**
* Dropoff Zone – **45 records**
* Pickup Borough – **26 records**
* Dropoff Borough – **45 records**

After applying appropriate imputation techniques, **0 missing values remained across all 14 variables**.

This improved the consistency and reliability of the dataset for analysis.

---

## 3. Payment Behavior

The payment-method analysis examines the distribution of **6,433 taxi trips** across different payment categories.

Understanding the most frequently used payment method can help taxi businesses:

* Identify customer payment preferences
* Improve payment facilities
* Prioritize convenient digital payment options
* Improve transaction tracking

---

## 4. Trip Distance

The trip-distance analysis shows that taxi trips are concentrated mainly around **shorter-distance journeys**, while longer-distance trips occur less frequently.

This suggests that frequent short-distance trips may contribute significantly to overall taxi trip volume.

---

## 5. Fare and Distance Relationship

The scatter plot demonstrates the relationship between **trip distance and fare**.

The analysis indicates that longer trips generally tend to generate higher fare amounts.

Therefore, trip distance is an important factor when evaluating **fare generation and revenue potential**.

---

## 6. Borough-Level Performance

Pickup borough analysis helps compare taxi demand across different geographical locations.

The borough with the highest trip volume can be considered an important area for:

* Fleet allocation
* Driver availability
* Demand forecasting
* Taxi positioning

Differences in tip distributions between boroughs can also provide insights into **customer tipping behavior**.

---

## 7. Revenue and Customer Value

The project analyzes **fare, tip, tolls, and total trip amount** together.

Combining these variables helps identify higher-value trips and provides a better understanding of overall customer spending.

This information can support:

* Revenue optimization
* Customer-value analysis
* Fare planning
* Operational decision-making

---

## 8. Correlation Analysis

A correlation heatmap was used to examine relationships between:

**Distance, Fare, Tip, Tolls, and Total Amount**

The analysis helps identify which variables have stronger relationships with overall trip revenue.

The relationship between **fare and total amount** is particularly useful because fare represents an important component of the total trip value.

The relationship between **distance and fare** also helps explain how trip length influences revenue.

---

# 🎯 Business Recommendations

Based on the analysis, the following recommendations can be considered:

1. **Optimize Fleet Allocation**
   Allocate more taxis and drivers to high-demand pickup boroughs.

2. **Monitor Long-Distance Trips**
   Analyze longer trips because they generally have greater revenue potential.

3. **Improve Payment Facilities**
   Provide convenient digital payment options based on customer preferences.

4. **Analyze Tip Patterns**
   Compare tipping behavior across boroughs to identify locations with higher customer-value potential.

5. **Improve Revenue Planning**
   Use the relationship between distance and fare to support fare and revenue planning.

6. **Maintain Data Quality**
   Perform regular missing-value and data-validation checks before conducting business analysis.

---

# 🔑 Key Takeaways

* **6,433** cleaned taxi trip records were analyzed.
* The dataset contains **14 variables**.
* Missing values were identified in **5 categorical columns**.
* After cleaning, **0 missing values remained**.
* Trip distance and fare were analyzed to understand revenue behavior.
* Payment methods were analyzed to understand customer preferences.
* Pickup boroughs were compared to understand geographical demand.
* Tips were analyzed to understand customer-value patterns.
* Correlation analysis was used to identify relationships between key financial and trip variables.

---

## 📈 Skills Demonstrated

* Python
* Pandas
* NumPy
* Data Cleaning
* Missing Value Handling
* Data Transformation
* Exploratory Data Analysis
* Matplotlib
* Seaborn
* Data Visualization
* Correlation Analysis
* Business Insight Generation

---

## 🏁 Conclusion

This project demonstrates the use of Python for cleaning, analyzing, and visualizing real-world-style taxi trip data. The analysis transforms raw trip information into meaningful insights related to **fare, distance, payment behavior, pickup locations, tips, and overall trip patterns**.

The project helped strengthen practical skills in **data analysis, exploratory data analysis, visualization, and business-oriented interpretation of data**.


---

## 👩‍💻 Author

**Sabana Asmi R**

**Data Analyst | SQL | Power BI | Python | Excel**

