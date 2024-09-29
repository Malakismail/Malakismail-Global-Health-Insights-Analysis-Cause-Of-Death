# Global Health Insights Analysis: Cause of Deaths

## Introduction
This project aims to provide a comprehensive analysis of global health data, focusing on the leading causes of death worldwide. By understanding the major factors contributing to global mortality, we can gain insights into healthcare trends, challenges, and opportunities to improve public health. The analysis leverages multiple data visualization techniques, including statistical modeling, to explore trends over time and across regions.

## Data Overview
The dataset used in this analysis contains information on various causes of death across different countries and years. It covers a wide range of factors contributing to mortality, providing a global perspective on the state of health and diseases.

## Objectives
- Identify the top causes of death globally.
- Perform regional analysis by countries and years.
- Trend analysis for specific causes such as Cardiovascular Diseases.
- Model forecasting for future trends based on historical data.
- Provide interactive and static visualizations to uncover insights.

## Dataset
The dataset titled `cause_of_deaths.csv` includes:
- **Year**: The year of the data point.
- **Country/Territory**: The country or territory the data pertains to.
- **Causes of Death**: Various causes of death, including Cardiovascular Diseases, HIV/AIDS, and Diabetes Mellitus.

## Process Details
1. **Data Preprocessing**: Missing values were handled, and data types were ensured to be correct (e.g., 'Year' as an integer).
2. **Exploratory Data Analysis (EDA)**: A summary of the data and initial insights were obtained through descriptive statistics and visualizations.
3. **Data Transformation**: The data was grouped by countries and years for regional analysis.
4. **Correlation Analysis**: A heatmap was generated to visualize correlations between different causes of death.
5. **Forecasting**: Using Linear Regression, Polynomial Regression, and Ridge models, forecasting was performed on the Cardiovascular Diseases data.

## Analysis
- **Top Causes of Death**: The global data was summarized to identify the most common causes of death. The top causes were plotted using bar charts.
- **Cardiovascular Diseases Trend**: A specific focus was placed on analyzing the trend of cardiovascular-related deaths over time.
- **Correlation Analysis**: Heatmap visualizations helped identify relationships between different causes of death.

## Key Insights 🌟
- Cardiovascular Diseases remain the leading cause of death globally, with increasing trends in several regions.
- There are strong correlations between certain causes of death, such as between Diabetes Mellitus and Cardiovascular Diseases.
- Countries show different trends, with some regions experiencing spikes in certain diseases during specific periods.

## Data Source
The data for this analysis is sourced from a global health dataset on causes of death. The dataset covers a wide range of causes of death from multiple countries over several years.

## Tools & Techniques Used
- **Programming Languages**: Python
- **Libraries**:
  - Data Manipulation: Pandas, Numpy
  - Visualization: Seaborn, Matplotlib, Plotly
  - Modeling: Scikit-learn (Linear Regression, Ridge, PolynomialFeatures)

## Results of Data Analysis Process
### Descriptive Statistics
- A summary of the number of deaths for each cause.
- Identification of outliers and missing data.

### Trends Over Time
- Cardiovascular Diseases have shown a consistent increase over the years globally.
- Other diseases like Diabeties have shown different regional and time-based patterns.

### Regional Analysis
- The data was grouped by country and year to show specific trends within countries.

### Visualizations
- Multiple static and interactive visualizations were created to highlight trends and insights.

### Modeling Results
- **Linear Regression**: R-squared score was calculated for the forecast of Cardiovascular Diseases.
- **Polynomial Regression**: A higher degree polynomial provided a more nuanced prediction.
- **Ridge Regression**: Used to handle multicollinearity and improve model stability.

## Conclusion
The analysis provided key insights into global health trends, particularly emphasizing the rise of cardiovascular diseases across the globe. The visualizations and modeling techniques used demonstrate significant patterns that can inform public health policies. Advanced techniques like Polynomial Regression and Ridge modeling offer more refined predictions for future trends.

## Contact
For inquiries or collaboration opportunities, please reach out to me:

**Name**: Malak Ismail  
**Email**: [malakismail706@gmail.com ](malakismail706@gmail.com )  
**LinkedIn**: [Malak Ismail](www.linkedin.com/in/malak-ismail-393148251)
