# EXPECTED OUTCOMES

## 0. Project Description / Overview

This project aims to analyze a Food Delivery Dataset to better understand the different factors that affect delivery performance and customer service efficiency. The dataset contains information about delivery personnel, restaurant locations, weather conditions, traffic density, vehicle types, order categories, and delivery times. The main goal of the project is to clean, organize, analyze, and visualize the dataset using Power BI in order to generate useful insights and support better decision-making.

The project also aims to create an interactive dashboard that can help businesses monitor delivery operations, improve delivery efficiency, evaluate rider performance, and understand how factors such as weather and traffic affect delivery time.

---

# 1. Data Collection Procedure

## a. Raw Dataset Profile

The dataset used in this project is a Food Delivery Dataset containing approximately 45,593 records and 20 attributes. The data includes:

| Column Name                            | Description                                    |
| -------------------------------------- | ---------------------------------------------- |
| ID                                     | Unique identifier of each delivery transaction |
| Delivery_person_ID                     | Unique ID of delivery personnel                |
| Delivery_person_Age                    | Age of delivery rider                          |
| Delivery_person_Ratings                | Performance rating of delivery rider           |
| Restaurant_latitude / longitude        | Restaurant location coordinates                |
| Delivery_location_latitude / longitude | Customer delivery location coordinates         |
| Order_Date                             | Date of order                                  |
| Time_Orderd                            | Time order was placed                          |
| Time_Order_picked                      | Time order was picked up                       |
| Weatherconditions                      | Current weather condition during delivery      |
| Road_traffic_density                   | Traffic level during delivery                  |
| Vehicle_condition                      | Condition of delivery vehicle                  |
| Type_of_order                          | Category of order                              |
| Type_of_vehicle                        | Vehicle used for delivery                      |
| multiple_deliveries                    | Number of deliveries handled                   |
| Festival                               | Indicates whether the day is a festival        |
| City                                   | City classification                            |
| Time_taken(min)                        | Total delivery time in minutes                 |

The dataset was gathered from a public machine learning repository and used for analysis and dashboard visualization purposes.

---

# 2. Data Cleaning Process / Documentation

Before the analysis, the dataset underwent several preprocessing and cleaning procedures using the CLEAN Framework to improve data quality and consistency.

## Data Cleaning and Preparation Tasks

| Cleaning Task         | Description                                                            | Expected Outcome                          |
| --------------------- | ---------------------------------------------------------------------- | ----------------------------------------- |
| Handle Missing Values | Removed rows with null or inconsistent values in important columns     | Improved dataset accuracy and reliability |
| Remove Duplicates     | Checked and removed duplicate records                                  | Prevented duplicated analysis results     |
| Data Transformation   | Converted text-based values into standardized formats                  | Improved readability and consistency      |
| Data Type Conversion  | Converted date and time columns into proper datetime format            | Enabled time-based analysis               |
| Normalization         | Standardized categorical values such as weather and traffic conditions | Reduced inconsistency in categories       |
| Feature Extraction    | Extracted useful insights from date and time fields                    | Supported trend analysis                  |
| Outlier Detection     | Identified abnormal delivery time values                               | Improved analytical accuracy              |

After the cleaning process, the dataset became more organized, accurate, and suitable for visualization and analytical processes.

---

# 3. Data Model (Star Schema)

The project will use a Star Schema data model to improve reporting efficiency and dashboard performance.

## Fact Table

### Fact_Delivery

Contains measurable delivery transaction information such as:

* Delivery Time
* Delivery Rating
* Vehicle Condition
* Multiple Deliveries

## Dimension Tables

### Dim_Delivery_Person

* Delivery Person ID
* Age
* Ratings

### Dim_Time

* Order Date
* Order Time
* Pickup Time
* Month
* Day
* Year

### Dim_Weather

* Weather Conditions
* Traffic Density
* Festival

### Dim_Location

* Restaurant Coordinates
* Delivery Coordinates
* City

### Dim_Order

* Type of Order
* Type of Vehicle

## Analytical Method Used

### Descriptive Analytics

The project will use descriptive analytics to:

* Analyze average delivery time
* Compare delivery performance across cities
* Evaluate the effect of weather and traffic on delivery duration
* Identify top-performing delivery personnel
* Observe delivery trends over time

### Predictive Analytics

The project may also use forecasting techniques to estimate future delivery times based on:

* Traffic density
* Weather conditions
* Vehicle condition
* Number of deliveries

---

# 4. Dashboard Wireframe Layout Following the DASH Framework

The dashboard will follow the DASH Framework to ensure that the visualizations are clear, interactive, and easy to understand.

## Proposed Dashboard Sections

### Header Section

* Project Title
* Date Filter
* City Filter

### KPI Cards

* Average Delivery Time
* Total Orders
* Average Rider Rating
* Total Delivery Personnel

### Visualization Area

* Bar Chart for Delivery Time by City
* Pie Chart for Vehicle Types
* Line Graph for Delivery Trends Over Time
* Heatmap for Traffic Density vs Delivery Time
* Weather Impact Analysis Chart

### Interactive Filters

* City
* Weather Condition
* Vehicle Type
* Festival Status
* Traffic Density

---

# 5. Visualization & Dashboard

The researchers will develop an interactive dashboard using Microsoft Power BI.

## Dashboard Features

* Dynamic filtering and slicers
* Interactive visualizations
* Drill-down functionality
* Real-time KPI monitoring
* User-friendly layout and navigation

## Key Performance Indicators (KPIs)

* Average Delivery Time
* Fastest Delivery Area
* Highest Rated Delivery Personnel
* Most Used Vehicle Type
* Traffic Impact on Delivery Time

The dashboard will provide a clear visual representation of delivery operations and help identify areas that need improvement.

---

# 6. Insights and Recommendations

## Expected Insights

1. High traffic density significantly increases delivery time.
2. Stormy and foggy weather conditions result in slower deliveries.
3. Motorcycle deliveries tend to have faster completion times compared to scooters.
4. Delivery personnel with higher ratings generally complete deliveries faster.
5. Metropolitan cities experience longer average delivery times due to congestion.

## Recommendations

1. Assign more riders during peak traffic hours to reduce delays.
2. Optimize delivery routing in metropolitan areas.
3. Prioritize motorcycle usage for faster delivery operations.
4. Improve rider training programs to increase service quality.
5. Implement weather-based delivery scheduling and notifications.

## Real-World Interpretation

The results of the analysis can help food delivery businesses improve operational efficiency, reduce customer waiting time, and increase customer satisfaction through data-driven decisions.

---

# 7. Expected Project Deliverables

The following outputs are expected upon completion of the project:

1. Cleaned Dataset
2. Power BI Dashboard (.pbix)
3. GitHub Repository Documentation
4. README File (.md or HTML)
5. Published Power BI Service Dashboard
6. Analytical Report and Presentation

---

# 8. Expected Outcome Summary

At the end of the study, the researchers expect to:

* Develop a fully functional Power BI dashboard for food delivery analytics.
* Generate accurate and meaningful delivery performance insights.
* Identify factors affecting delivery delays and operational efficiency.
* Provide data-driven recommendations for improving food delivery services.
* Demonstrate the effectiveness of descriptive and predictive analytics in business operations.

Overall, the project is expected to contribute to better delivery management strategies and improved customer experience in the food delivery industry.
