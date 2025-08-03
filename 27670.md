# **👤 Student Profile**  

🔹 **NAME:** NGABONZIZA Kim Gakuba  
🔹 **ID:** `27670`  
🔹 **GROUP:**  **A**  

---


# 💧 Efficient Water Use in Agriculture: A Key to Sustainability

# FAOSTAT Agriculture Dashboard

My Power BI dashboard provides comprehensive insights into global agricultural land use and water management, helping stakeholders evaluate efficiency and vulnerability in water-scarce areas. The dashboard analyzes data from FAO (Food and Agriculture Organization) to track agricultural trends and resource utilization patterns.

## Dashboard Overview

### Water Efficiency Challenge
This opening page presents key performance indicators for global agricultural land utilization. It displays critical metrics including the total irrigated agriculture area (8.36 units), land equipped for irrigation infrastructure (422.79 units), and total cropland area (79.97K units). The page includes interactive filters for year range selection and unit preferences, enabling users to customize their analysis timeframe and measurement units.

<img width="1600" height="900" alt="page1" src="https://github.com/user-attachments/assets/e32c8452-a531-4782-a07c-a36d08f55b82" />


---

### Trends in Irrigated Agriculture Over Time
The trends analysis page features dual line charts that visualize the evolution of agricultural metrics across different time periods. The left chart shows the sum of values by year, while the right chart displays sum of values by area code over time. These visualizations reveal growth patterns, seasonal variations, and long-term trends in agricultural development, helping identify periods of significant change or stable growth.

<img width="1600" height="900" alt="page2" src="https://github.com/user-attachments/assets/fa7327a0-307e-47c3-a533-0e1dd68a0dbc" />

---

### Country Ranking by Irrigated Land
This page provides a detailed bar chart analysis showing the distribution of area codes and their corresponding values over time. The visualization displays year-over-year comparisons and allows for drill-down analysis into specific regions or countries. Interactive sliders enable users to filter data by specific time ranges, making it easy to focus on particular periods of interest for regional agricultural analysis.

<img width="1600" height="900" alt="page3" src="https://github.com/user-attachments/assets/3fb5fae6-cc04-4f79-a378-253d12fd48b9" />

---

###  Water Efficiency Analysis
The geographic visualization page presents a spatial analysis of agricultural data across different regions. This map-based view shows the distribution of agricultural metrics by item code, providing a clear geographic perspective on where agricultural activities are concentrated. The visualization helps identify regional patterns, hotspots of agricultural activity, and areas that may require additional attention or resources.

<img width="1600" height="900" alt="page4" src="https://github.com/user-attachments/assets/cf523e06-ad5c-40ef-ba37-047cb576e49f" />

---

### Interactive Exploration & Filtering
This comprehensive metrics page displays key agricultural statistics with precise numerical values. It shows the sum of values by year (15.34K), area code analysis (6.63E-12), and total agricultural metrics (794.05K). These detailed figures provide stakeholders with exact measurements needed for reporting, planning, and decision-making processes in agricultural resource management.

<img width="1600" height="900" alt="page5" src="https://github.com/user-attachments/assets/3bffc06e-9b67-4fb4-a230-2b0c19c91ede" />

---

### Executive Dashboard Overview
The final page serves as an executive summary combining multiple visualization types in a single comprehensive view. It features trend lines, bar charts, pie charts, and key performance indicators (433.93K and 12.83K metrics) along with comparative analysis (-705.68). This integrated dashboard provides decision-makers with a complete picture of agricultural performance, enabling quick assessment of overall trends and identification of areas requiring immediate attention.

<img width="1600" height="900" alt="page6" src="https://github.com/user-attachments/assets/64b20173-4623-4eb4-9d5e-8b336cf4fe79" />

---

## Key Features

- **Interactive Filtering**: Cross-page filtering capabilities allowing users to analyze specific time periods, regions, or agricultural categories
- **Multiple Visualization Types**: Line charts, bar charts, maps, and KPI cards providing diverse analytical perspectives
- **Drill-through Functionality**: Ability to navigate between different levels of detail for comprehensive analysis
- **Real-time Data Processing**: Dynamic calculations and aggregations based on selected filters
- **Export Capabilities**: Options to export visualizations and data for external reporting and presentations

## Data Sources

My dashboard utilizes FAOSTAT (Food and Agriculture Organization Corporate Statistical Database) data, providing reliable and standardized agricultural statistics from around the world. The data includes metrics on land use, irrigation systems, crop production, and agricultural efficiency indicators.

## Usage Instructions

1. Use the year sliders to filter data for specific time periods
2. Select unit preferences (1000 ha, ha cap, million t, USD_2019 ha) based on your analysis needs
3. Click on visual elements to cross-filter related charts


# Agriculture Data Analysis Project

This project performs comprehensive data analysis on agricultural datasets, focusing on data cleaning, exploratory data analysis, and predictive modeling to understand agricultural trends and patterns.

## Dataset Overview

The project works with an agricultural dataset containing 1,675 entries across 15 columns, including:
- **Domain Code & Domain**: Land use classifications
- **Area Code & Area**: Geographic regions (primarily Rwanda)
- **Element Code & Element**: Measurement types
- **Item Code & Item**: Agricultural items/products
- **Year Code & Year**: Time period (1961-2022)
- **Unit**: Measurement units
- **Value**: Quantitative measurements
- **Flag & Flag Description**: Data quality indicators

<img width="1600" height="900" alt="output1" src="https://github.com/user-attachments/assets/11c07ec3-ed2d-4103-8725-d5cc2140a31d" />


## Data Preprocessing

### Missing Value Analysis
The initial analysis revealed missing values across multiple columns:
- Most columns had 0 missing values after initial cleaning
- **Note** column had 1,675 missing values (completely empty)
- Applied threshold-based filtering to remove columns with >50% missing values

### Data Cleaning Steps
1. **Missing Value Imputation**: Numerical columns were imputed using median values
2. **Outlier Detection**: Applied statistical methods to identify and handle outliers
3. **Data Type Optimization**: Separated numerical and categorical columns for appropriate processing

<img width="1600" height="900" alt="output2" src="https://github.com/user-attachments/assets/56ba85ab-913b-45cb-bfbd-61ffb8d1845b" />


## Exploratory Data Analysis

### Distribution Analysis
The project includes comprehensive visualization of data distributions:

#### Value Distribution
- Shows the frequency distribution of agricultural values
- Reveals data concentration patterns and potential outliers
- Most values cluster around lower ranges with some high-value outliers

<img width="1600" height="900" alt="output3" src="https://github.com/user-attachments/assets/3312b258-ba47-482c-b4d1-612c3982074e" />


#### Temporal Analysis
- Year distribution shows data collection patterns from 1960s to 2020s
- Identifies periods of increased data collection activity
- Reveals temporal trends in agricultural measurements

### Outlier Analysis
Applied statistical outlier detection and capping techniques:
- Used box plots to visualize outliers in the Value column
- Implemented outlier capping to maintain data integrity while preserving meaningful patterns

<img width="1600" height="900" alt="output4" src="https://github.com/user-attachments/assets/01cdc36e-66df-45a6-81f2-e03e4fcc6114" />


## Time Series Analysis

### Trend Visualization
Created comprehensive time series analysis showing:
- **Total Value Over Years**: Demonstrates agricultural trends from 1960-2020
- Shows significant periods of growth (1960s-1990s) and subsequent fluctuations
- Identifies key transition periods in agricultural patterns

<img width="1600" height="900" alt="output5" src="https://github.com/user-attachments/assets/57805910-d8c9-430c-83e6-f076e8351697" />


## Predictive Modeling

### Linear Regression Analysis
Implemented predictive modeling to understand relationships within the agricultural data:

**Model Performance:**
- **RMSE (Root Mean Squared Error)**: 1.03
- **R-squared (R²)**: -0.01

### Model Evaluation
- **Actual vs. Predicted Plot**: Shows the relationship between predicted and actual values
- The scatter plot reveals model limitations, with most predictions clustering around zero
- Red dashed line represents perfect prediction (y = x)

<img width="1600" height="900" alt="output6" src="https://github.com/user-attachments/assets/4cbf5be6-7ba4-4788-bc15-d38f1a21f0a8" />


## Key Findings

1. **Data Quality**: Successfully cleaned and preprocessed agricultural dataset with minimal data loss
2. **Temporal Patterns**: Identified distinct periods of agricultural development and change
3. **Distribution Insights**: Most agricultural values concentrate in lower ranges with notable outliers
4. **Model Limitations**: Current linear regression model shows poor predictive performance (R² ≈ 0), suggesting need for more complex modeling approaches

## Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **Scikit-learn**: Machine learning and statistical modeling
- **Jupyter Notebook**: Development environment

## Future Improvements

1. **Advanced Modeling**: Implement ensemble methods, time series forecasting models
2. **Feature Engineering**: Create additional features from temporal and categorical data
3. **Cross-validation**: Implement robust model validation techniques
4. **Deep Learning**: Explore neural networks for complex pattern recognition
