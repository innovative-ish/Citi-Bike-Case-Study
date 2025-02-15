# Citi-Bike-Case-Study
Citi Bike Case Study
Project Overview
This project analyzes Citi Bike demand patterns to optimize bike allocation at stations, ensuring maximum daily trips. Using historical data, we explore peak usage trends, weather impacts, and predictive modeling to enhance Citi Bike’s operational efficiency.

**Objectives**

- Predict bike demand for September 6, 2018.
- Identify peak hours and trip distribution between stations.
- Determine optimal bike allocation at each station.
- Analyze the impact of weather factors on demand.
- Propose a data-driven strategy for efficient bike-sharing.

**Data & Methodology**

- Dataset: 31,414 trip records with 25 attributes.
- Techniques Used:

  Descriptive statistics (mean, standard deviation, correlation).
    
  Data visualization using ggplot2.
    
  Predictive modeling with linear regression.
  
**Key Findings:**

- Higher demand on weekdays, peaking in the evening.
- Short trips (5-10 minutes) are the most frequent.
- Snowfall decreases bike demand, while temperature has minimal impact.
- Linear regression model predicts 1,582 trips with 997 bikes allocated.

**Business Recommendations**

- Improve bike availability at high-demand stations.
- Implement dynamic rebalancing based on demand forecasts.
- Explore corporate partnerships and advertising for revenue growth.
  
**Technologies Used**

  - Programming: R
  - Libraries: ggplot2, dplyr
  - Tools: RStudio, Excel

**How to Run the Project**

1. Clone the repository:

       git clone https://github.com/yourusername/citi-bike-case-study.git  
       cd citi-bike-case-study  
3. Open the R script in RStudio.
4. Run the data preprocessing and visualization steps.
5. Execute the regression model for demand prediction.

**Contributors**
* Ishita Agrawal
* Kamaldeep Kaur
* Calen McKinney
* Aamir Sohail Mohammed
* Maliha Nadeem
* Kiran Subramani

**License**
**This project is open-source under the MIT License.**
