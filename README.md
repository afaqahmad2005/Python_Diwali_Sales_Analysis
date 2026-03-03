Diwali Sales Data Analysis

This project performs exploratory data analysis (EDA) on Diwali sales data to understand customer behavior, purchasing patterns, and sales performance across different demographics and product categories.

📊 Dataset Overview

The dataset contains 11,239 records after cleaning, with 13 features including customer demographics, product information, and transaction details.

Features:
- User_ID: Unique customer identifier
- Cust_name: Customer name
- Product_ID: Product identifier
- Gender: Customer gender (M/F)
- Age Group: Age category (0-17, 18-25, 26-35, 36-45, 46-50, 51+)
- Age: Customer age
- Marital_Status: Marital status (0: Unmarried, 1: Married)
- State: Customer state
- Zone: Geographic zone
- Occupation: Customer occupation
- Product_Category: Product category purchased
- Orders: Number of orders
- Amount: Transaction amount

🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

📋 Data Cleaning Steps

1. Removed unnecessary columns (`Status`, `unnamed1`)
2. Handled missing values (12 null values in Amount column)
3. Converted Amount data type from float to integer
4. Renamed columns for better readability

📈 Key Insights

1. Gender Analysis
- Majority of buyers are female
- Females have higher purchasing power** compared to males
- Total sales by gender:
  - Female: ₹74,335,856
  - Male: ₹31,913,276

2. Age Group Analysis
- Most buyers are in the 26-35 age group
- Female buyers dominate across all age categories
- The 26-35 age group contributes the highest sales amount

3. Geographic Analysis
- Top 5 states by orders:
  - Uttar Pradesh
  - Maharashtra
  - Karnataka
  - Delhi
  - Madhya Pradesh
- These states also show the highest sales amounts

4. Marital Status Impact
- Married women are the primary buyers
- Married individuals show higher purchasing power
- Married women significantly outspend other demographics

5. Occupation Analysis
- Top occupations by sales:
  - IT Sector
  - Healthcare
  - Aviation
  - Banking
  - Government sector

6. Product Category Performance
- Most popular product categories:
  - Food
  - Clothing & Apparel
  - Electronics & Gadgets
  - Footwear
  - Furniture

7. Top Selling Products
- Identified top 10 most ordered products
- Product IDs with highest order counts:
  - P00265242
  - P00110942
  - P00237842
  - (and more...)

🎯 Conclusion

Target Customer Profile:**
- Age: 26-35 years
- Gender: Female
- Marital Status: Married
- Location: Uttar Pradesh, Maharashtra, Karnataka
- Occupation: IT, Healthcare, Aviation sectors
- Preferred Categories: Food, Clothing, Electronics

📊 Visualizations

The analysis includes various visualizations:
- Count plots for categorical variables
- Bar charts for sales by different segments
- Comparative analysis using grouped bar charts
- Top 10 rankings for various metrics

🚀 How to Run

1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Place the 'Diwali Sales Data.csv' file in the project directory
4. Run the Jupyter notebook or Python script

📝 Future Scope

- Time series analysis to identify sales trends
- Predictive modeling for customer segmentation
- Product recommendation system based on customer profiles
- Seasonal pattern analysis
- Price elasticity analysis

📁 Repository Structure

```
├── Diwali Sales Data.csv          # Raw dataset
├── Diwali_Sales_Analysis.ipynb    # Main analysis notebook
├── README.md                       # Project documentation
└── requirements.txt                # Required Python packages
```

🤝 Contributing

Feel free to fork this repository and contribute by:
- Adding more analysis techniques
- Improving visualizations
- Implementing machine learning models
- Enhancing documentation

📄 License

This project is open-source and available for educational and research purposes.