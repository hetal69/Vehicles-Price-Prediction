# Car Selling Price Analysis

In the competitive landscape of automobile sales, determining a car's selling price involves various factors like brand perception, vehicle condition, and market trends. This project utilizes a dataset of 118,412 car sale records to uncover patterns influencing car prices using data mining techniques. The goal is to provide actionable insights for the automotive industry, guiding pricing strategies and improving understanding of consumer preferences.

**Key Objectives:**

   - Analyze the 'data3.csv' dataset to identify significant factors affecting car prices.
   - Explore relationships between attributes like year, make, model, and condition to understand their influence on pricing.
   - Visualize key trends and insights to make data-driven conclusions.

**Methodology:**

   - **Data Cleaning:** Handled missing values, removed irrelevant columns (e.g., sale date), and used the Interquartile Range (IQR) method for outlier detection.
   - **Data Preparation:** Scaled numerical features and encoded categorical variables for analysis.
   - **EDA & Visualization:** Generated scatter plots, box plots, and pie charts to visualize trends in car conditions, mileage, make, color, and transmission types.
   - **Tools:** Python, Pandas, Seaborn, Matplotlib, and Scikit-learn for data handling, visualization, and statistical analysis.

**Key Findings:**

   - Vehicle condition, make, model, year, and odometer readings strongly correlate with selling prices.
   - Outliers in 'selling price' data indicate rare or luxury vehicles, which could skew average pricing trends.
   - The preference for automatic transmission and specific colors and makes significantly impact car sales.

**Exploratory Data Analysis (EDA) and Visualizations:**

The visualizations generated from the dataset highlighted several important trends:

   **Boxplot Analysis:** A positive skew in the distribution of 'sellingprice' was observed, with outliers indicating the sale of luxury or rare vehicles, which significantly affect the average pricing.
   
   **Scatter Plots:** Clusters emerged when plotting 'sellingprice' against 'odometer' readings and 'condition', illustrating the depreciation of vehicle value as mileage increases and condition worsens.
   
   **Pie Charts:** A clear preference for automatic transmissions was evident in the dataset, indicating a dominant trend among the vehicles sold.
   
   **Bar Charts:** Certain car makes and colors were favored, suggesting these factors may influence selling prices and consumer demand.
   
   **Line Charts:** A noticeable upward trend in selling prices over the years could be attributed to inflation or shifts in consumer preferences toward higher-priced models.

          ![image](https://github.com/user-attachments/assets/d867f115-c293-4947-84e0-d65f05ddd986)
