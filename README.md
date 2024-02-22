# Bike Sales-analysis

## Table of content

- [Project Overview](#project-overview)
- [Data sources](#data-sources)
- [Tool](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)
## Project Overview

This data analysis project aims to provide insights into the sales performance of Bikes all over Europe over the year. By analyzing various aspects of the sales data, we seek to identify trends, make data driven recommendations, and gain a deeper understanding of the bikes sales perfromance.

### Data sources

Sales Data: The primary dataset used for this analysis is the 'Europe bike_sales.cvs' file, containing detailed information about each sales made in Europe

### Tools

- Excel - Data Cleaning,
  - Data Analysis,
  - Creating reports
  - [Download_Here](https://microsoft.com)




  ### Data Cleaning/Preparation

  In the initial data preparation phase, we performed the following tasks:
  1. Data Loading and inspection.
  2. Handling missing values
  3. Data cleaning and formatting
 

  ### Exploratory Data Analysis

  EDA involved exploring the sales data to answer questions such as:

  - What is the overall sales trend?
  - which product_category are top sellers?
  - which country in Europe purchase bike most ?

    ### Data Analysis

    ``` Excel
    =IF(D2>54,"Old",IF(D2>=31,"Middle Age",IF(D2<31,"Adolescent","invalid")))
    ```

    ### Results/Findings
    The analysis results are summarized as follows:
    - The bikes sales across Europe has been steadingly decreasing over the past years, with a noticeable peak between 2011 and 2016 .
    - Prodct category_Bikes is the best performing category in terms of sales and revenue,
    - Female gender should both the adolescents and adults should be targeted for marketing efforts.

    ### Recommendations

    Based on the analysis, we recommend the following actions:
    - Invest in marketing and promotion to maximise revenue
    - focus on expanding and promoting products category_ Accesory,
    - Implement a customer segmentation startegy to target high income customers effectively.
   
 ### Limitations
- I had to remove all zero values from cost and revenue by country colums because they would have affected the accuracy of my cocnclusion from the analysis. There are still a few outliers even after the ommission but even then we can still see that there is a Positive correllation between both budget and number of votes with revenue

  ### References

  1. Excel for Businesses by Career Principles
  2. [Stack-Overflow]
  3. [Alex-the-Analyst]
