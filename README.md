# Exploratory Data Analysis (EDA) of Shopping Data

This repository contains an exploratory data analysis (EDA) of a shopping dataset using Python and Jupyter Notebook. The goal of this project is to analyze and visualize the dataset to uncover insights about customer behavior, purchasing patterns, and other trends.

---

## **Dataset**
The dataset used in this analysis is `Mall_Customers.csv`. It contains information about customer purchases, including:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned to the customer based on their purchasing behavior.

---

## **Analysis Overview**
In this notebook, I aim to answer the following questions based on the attached dataset, which contains information about customer demographics, their shopping preferences, product categories, purchase amounts, and related details such as payment methods, shipping types, and subscription statuses.

### **Questions:**
1. **What are the most frequently purchased product categories in different seasons?**  
2. **Is there a relationship between the customer's age and the average review rating given by them?**
3. **Which product color is the most popular among customers from different locations?**
4. **What payment methods are preferred by customers depending on the frequency of their purchases?**
5. **Do customers with a subscription ("Subscription Status") use promotional codes more frequently?**

Before diving into answering the questions, the dataset is reviewed to understand its structure, check for missing values, and perform any necessary cleaning steps. This ensures the analysis is accurate and reliable.

The analysis includes the following steps:
1. **Data Loading and Inspection**:
   - Loaded the dataset into a Pandas DataFrame.
   - Checked for missing values, duplicates, and data types.
2. **Descriptive Statistics**:
   - Calculated summary statistics (mean, median, standard deviation, etc.) for numerical columns.
   - Analyzed the distribution of categorical variables (e.g., gender).
3. **Data Visualization**:
   - Created visualizations to explore relationships between variables:
     - Histograms for age, annual income, and spending score.
     - Scatter plots to analyze correlations (e.g., age vs. spending score, annual income vs. spending score).
     - Box plots to compare spending scores across genders.
4. **Insights and Conclusions**:
   - Identified trends and patterns in the data.
   - Provided actionable insights based on the analysis.

---

## **Technologies Used**
- **Python**: Programming language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib and Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive coding and documentation.

---

## **How to Run the Code**
1. Clone this repository:
   ```bash
   git clone https://github.com/J0yfarah/EDA-of-Shopping-Data.git