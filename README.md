# Hospitality Analytics

## Project Overview
This repository showcases a comprehensive data analysis project focused on the hospitality industry. The goal is to leverage data-driven insights to optimize business performance and operational efficiency. The project encompasses the entire data lifecycle—from data ingestion and cleaning to exploratory data analysis (EDA), feature engineering, statistical analysis, and interactive dashboard creation.

## Data Sources and Description
The analysis uses multiple CSV files, including:
- **dim_date**: Contains date-related details such as week numbers and day types.
- **dim_hotels**: Provides hotel information including property IDs, names, categories (Luxury, Business), and locations.
- **dim_rooms**: Describes various room types and classifications (Standard, Elite, Premium, Presidential).
- **fact_aggregated_bookings**: Aggregates booking data by check-in dates, successful bookings, and capacity details.
- **fact_bookings**: Contains individual booking records including booking dates, check-in/out dates, guest counts, booking platforms, ratings, statuses, and revenue metrics.

For detailed metadata on these datasets, refer to the [Meta Data Documentation](./meta_data_hospitality.txt) :contentReference[oaicite:0]{index=0}.

## Key Performance Indicators (KPIs)
The project tracks several essential KPIs on a week-over-week (WoW) basis:
- **Revenue WoW Change %**: Percentage change in revenue between consecutive weeks.
- **Occupancy WoW Change %**: Variation in occupancy rates from week to week.
- **ADR (Average Daily Rate) WoW Change %**: Changes in the average daily rate.
- **RevPAR (Revenue Per Available Room) WoW Change %**: Trends in revenue per available room.
- **Realisation WoW Change %**: Week-over-week change in revenue realisation.
- **DSRN (Daily Sellable Room Nights) WoW Change %**: Shifts in the number of sellable room nights.


## Data Analysis Methodology
The project follows a structured data analysis approach:

1. **Exploratory Data Analysis (EDA):**  
   - Investigate data distributions, identify outliers, and understand missing value patterns.
   - Visualize key trends and correlations to drive hypothesis generation.

2. **Data Cleaning and Preparation:**  
   - Standardize and normalize data from multiple sources.
   - Merge and integrate datasets to form a consolidated data repository, ensuring high data quality.

3. **Feature Engineering:**  
   - Derive new metrics and features (e.g., WoW percentage changes) to capture complex business dynamics.
   - Utilize domain knowledge to enhance the dataset and improve model performance.

4. **Statistical Analysis and Modeling:**  
   - Apply descriptive statistics and hypothesis testing to validate assumptions.
   - Develop predictive models, if applicable, to forecast future trends and support decision-making.

5. **Data Visualization and Dashboarding:**  
   - Create interactive dashboards with dynamic filtering and drill-down capabilities.
   - Employ best practices in data visualization to ensure clear and impactful storytelling.

## Tools and Technologies
This project leverages a variety of tools and technologies to ensure robust analysis:
- **Data Processing & Analysis:** Python, R, and SQL for data manipulation, statistical analysis, and feature engineering.
- **Visualization & Reporting:** Power BI and Excel for interactive dashboarding and visual storytelling.
- **Version Control:** Git for managing code and collaboration.

## Dashboard Overview
The interactive dashboard visualizes key metrics and trends. It includes filters, dynamic charts, and drill-down features to explore the data from multiple perspectives.

**Dashboard Screenshots:**

![Dashboard Screenshot](https://github.com/user-attachments/assets/18483021-ef80-42d2-bece-d5801565772c)


![Data Model](https://github.com/user-attachments/assets/20ec83b9-3841-4c8b-85b2-04e70d17f562)

## Best Practices and Data Analysis Philosophy
- **Data-Driven Decision Making:**  
  Utilize quantitative analysis to guide business strategies and operational improvements.
  
- **Iterative Analysis:**  
  Embrace an iterative process where hypotheses are continuously tested, validated, and refined.
  
- **Transparency and Reproducibility:**  
  Document each step of the analysis to ensure clarity and reproducibility of results.
  
- **Visual Storytelling:**  
  Present insights in a clear, engaging manner to support strategic discussions and decision-making.

## How to Run the Project
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/yourusername/hospitality-analytics.git
   cd hospitality-analytics
