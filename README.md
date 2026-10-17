# Mobile_user_behaviour_analysis_using_excel

## Project Overview

The **Mobile Usage Insights Dashboard** is an interactive data analytics project developed using Microsoft Excel, Power Query, PivotTables, and charts to analyze smartphone usage patterns across different age groups, genders, and user behavior categories.

The project transforms raw user behavior data into an interactive dashboard that tracks app usage time, screen time, mobile data consumption, and the number of installed applications. It helps explore usage patterns, compare demographic groups, and examine relationships between mobile usage metrics.

## Business Problem

Understanding smartphone usage behavior requires analyzing multiple variables, including daily app usage, screen time, data consumption, installed applications, age, and gender.

Raw datasets make it difficult to identify patterns and compare user segments efficiently. This project addresses the problem by cleaning and transforming the source data, aggregating key metrics using PivotTables, and presenting the results through an interactive Excel dashboard.

## Tools & Technologies

- Microsoft Excel
- Power Query Editor
- Excel PivotTables
- Excel formulas and calculated columns
- Interactive slicers
- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- KPI development and dashboard visualization
- Demographic and behavioral analysis

## Dataset Overview

The dataset contains **700 user records** and 11 columns after the Power Query transformations shown in the project.

Key attributes include:

- **User Information:** User ID, Device Model, Operating System
- **Usage Metrics:** App Usage Time (hours/day), Screen On Time (hours/day)
- **Device Metrics:** Battery Drain (mAh/day), Number of Apps Installed, Data Usage (MB/day)
- **Demographic Attributes:** Age, Gender
- **Behavioral Attributes:** User Behavior Class

## Data Cleaning & Transformation Using Power Query

Power Query was used to prepare the dataset for analysis through a sequence of transformation steps visible in the query editor.

- Promoted the first row to column headers and assigned appropriate data types.
- Removed blank rows and duplicate records.
- Corrected the User ID and behavior-related column types.
- Created a custom age field and grouped users into age categories.
- Renamed and standardized age and behavior-related columns.
- Created and transformed app usage values using custom columns and rounding operations.
- Reordered columns and removed obsolete intermediate columns.
- Reviewed column quality, validity, distinct values, and data distribution using Power Query profiling features.

These transformations established a consistent dataset for PivotTable calculations and dashboard reporting.

## Key Performance Indicators (KPIs)

The dashboard summarizes the following metrics across 700 users:

| KPI | Reported Value |
|---|---:|
| Total Users | 700 |
| Average App Usage | 4.5 hours/day |
| Average Screen Time | 5.3 hours/day |
| Average Data Usage | 929.7 MB/day |
| Average Apps Installed | 51 |

## Dashboard Features & Analysis

### 1. App Usage by Age Group
Compares average daily app usage across four age groups: 18–25, 26–35, 36–45, and 46–59.

### 2. Screen Time by Age Group
Evaluates differences in average daily screen time across age categories.

### 3. Data Usage by Age and Gender
Uses a stacked column chart to compare average mobile data consumption across age groups and genders.

### 4. App Usage vs. Data Usage
Uses a scatter plot and trendline to explore the relationship between daily app usage time and mobile data consumption.

### 5. Installed Applications vs. App Usage
Visualizes the relationship between the number of installed applications and daily app usage time.

### 6. App Usage by Gender
Compares average daily app usage between male and female users.

### 7. Interactive Dashboard Filtering
Includes slicers for:
- Gender
- Age Group
- User Behavior Class

The slicers allow users to explore usage patterns across different demographic and behavioral segments.

## Key Analytical Takeaways

- Average daily screen time is higher than average app usage time in the overall dataset.
- The 46–59 age group has the highest displayed average app usage and screen time among the four age groups.
- Average app usage is very similar for male and female users in the displayed results.
- The scatter plots suggest positive relationships between app usage time and data consumption, and between installed applications and app usage time. These relationships should be validated statistically before drawing stronger conclusions.

## Project Workflow

1. **Data Preparation:** Imported the user behavior dataset into Power Query.
2. **Data Cleaning:** Removed blank rows and duplicates, corrected data types, and standardized fields.
3. **Data Transformation:** Created age groups and transformed usage and behavior-related columns.
4. **Data Aggregation:** Built PivotTables to calculate average usage metrics across age, gender, and application-related dimensions.
5. **Data Visualization:** Developed KPI cards, column charts, bar charts, and scatter plots with trendlines.
6. **Dashboard Development:** Combined the visualizations into an interactive dashboard with slicers for demographic and behavioral analysis.

## Project Outcome

Developed an interactive Excel dashboard that converts 700 user records into a consolidated view of smartphone usage behavior. The project demonstrates an end-to-end Excel analytics workflow involving data preparation, Power Query transformations, PivotTable-based aggregation, KPI reporting, exploratory analysis, and interactive visualization.

## Skills Demonstrated

Power Query, Data Cleaning, Data Transformation, Microsoft Excel, PivotTables, Exploratory Data Analysis, KPI Reporting, Data Visualization, Dashboard Development, Demographic Analysis, Trendline Analysis, and Business Insights.

## Resume-Ready Project Description

**Mobile Usage Insights Dashboard | Microsoft Excel, Power Query**

- Cleaned and transformed 700 user records using Power Query, including duplicate removal, data type standardization, age-group categorization, and usage-field transformations.
- Developed PivotTables and an interactive Excel dashboard to analyze app usage, screen time, data consumption, and installed applications across age groups and genders.
- Created KPI cards, comparative charts, and scatter plots with trendlines, incorporating slicers for gender, age group, and user behavior class.

