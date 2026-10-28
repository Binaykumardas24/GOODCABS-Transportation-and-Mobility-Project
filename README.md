# GOODCABS-Transportation-and-Mobility-Project
# 🚖 GoodCabs Transportation & Mobility Analytics

## 📌 Project Overview

The GoodCabs Transportation & Mobility Analytics project focuses on evaluating cab service performance across 10 Indian Tier-2 cities. The analysis explores trip performance, revenue contribution, passenger satisfaction, repeat passenger behavior, and target achievement to identify business opportunities and operational challenges.

The goal is to turn transportation data into actionable insights that support customer retention, business growth, and improved service quality.

## 🎯 Project Objectives

- Analyze trip volume and revenue contribution across cities.
- Evaluate average fare per trip and average fare per kilometer.
- Compare passenger and driver ratings across locations.
- Identify trends in new and repeat passenger behavior.
- Analyze monthly, weekday, and weekend trip demand.
- Measure actual performance against business targets.
- Use SQL to solve ad-hoc business questions.
- Develop data-driven recommendations for business improvement.

## 🛠️ Tools & Technologies

- **SQL:** Business queries, data analysis, performance comparisons, and ad-hoc requests.
- **Microsoft Excel:** Data organization, analysis, and stakeholder-friendly reporting.
- **Data Analytics:** KPI tracking, trend analysis, passenger segmentation, and business insights.
- **Dashboard Reporting:** Visual presentation of business performance.

## 📂 Dataset Overview

The project uses the following datasets:

- `fact_trips.csv`
- `fact_passenger_summary.csv`
- `dim_city.csv`
- `dim_date.csv`
- `dim_repeat_trip_distribution.csv`
- `monthly_target_trips.csv`
- `monthly_target_new_passengers.csv`
- `city_target_passenger_rating.csv`

The project also uses the `trips_db` and `targets_db` databases to answer ad-hoc business questions.

## 📊 Key Business Insights

### 1. City-Level Trip Performance

- Jaipur recorded approximately **77K trips**, making it the highest-performing city by trip volume.
- Lucknow followed with approximately **64K trips**, while Surat recorded approximately **55K trips**.
- Mysore recorded approximately **16K trips**, the lowest trip volume among the analyzed cities.
- Jaipur, Lucknow, Surat, and Kochi together contributed **58.12% of total trip volume**.

### 2. Revenue & Pricing Analysis

- Jaipur generated approximately **₹37.21 million in revenue**, contributing around **34% of total revenue**.
- Jaipur recorded the highest average fare per trip at **₹483.92** and the longest average trip distance at **30.02 km**.
- Surat recorded the lowest average fare per trip at **₹117.27**.
- The analysis highlighted differences in fare levels, trip distances, and revenue contribution across cities.

### 3. Passenger Satisfaction

- Mysore recorded the highest average passenger rating at **8.70**.
- Jaipur followed with **8.58**, while Kochi recorded **8.52**.
- Surat recorded the lowest average passenger rating at **6.42**, followed by Lucknow at **6.49** and Vadodara at **6.61**.

### 4. Repeat Passenger Analysis

- Surat recorded the highest repeat passenger rate at **42.63%**, followed by Lucknow at **37.12%**.
- Mysore recorded the lowest repeat passenger rate at **11.23%**, while Jaipur recorded **17.41%**.
- The repeat passenger rate was highest in May at **33.47%** and lowest in January at **18.68%**.
- The analysis identified opportunities to improve passenger retention, particularly in cities with lower repeat usage.

### 5. Target Performance Analysis

- Mysore exceeded its trip target by **20.28%**, while Jaipur exceeded its target by **13.91%**.
- Vadodara recorded the largest trip-target shortfall at **14.60% below target**.
- Coimbatore achieved the strongest new-passenger growth against target at **13.52% above target**.
- Jaipur recorded a new-passenger acquisition shortfall of **15.08% below target**.
- Lucknow and Vadodara required attention because they missed their targets across the analyzed months.

### 6. Demand & Seasonal Trends

- February, April, and May showed higher trip volumes across cities.
- January and June experienced lower trip demand.
- Tourism-focused cities such as Jaipur, Mysore, and Kochi showed stronger weekend demand.
- Business-focused cities such as Lucknow, Surat, Vadodara, and Coimbatore showed stronger weekday demand.

## 💡 Business Recommendations

- **Improve passenger retention:** Introduce loyalty programs and targeted offers to encourage repeat bookings.
- **Strengthen service quality:** Investigate low passenger ratings in Surat, Lucknow, and Vadodara.
- **Optimize pricing:** Review fare structures in cities with lower average fares and revenue contribution.
- **Improve new-passenger acquisition:** Develop targeted campaigns in cities that are missing new-passenger targets.
- **Plan for seasonal demand:** Use festivals, holidays, and local events to improve demand forecasting and promotional planning.
- **Build local partnerships:** Collaborate with hotels, airports, railway stations, commercial hubs, and event venues.
- **Monitor KPIs regularly:** Track trip volume, revenue, passenger ratings, repeat passenger rates, and target achievement.

## 📈 Project Outcome

This project demonstrates how SQL-based analysis and Excel reporting can help identify performance gaps, understand customer behavior, evaluate business targets, and generate actionable recommendations.

It highlights the importance of combining operational metrics, customer insights, and target-performance analysis to support data-driven decisions in the transportation and mobility industry.

## 📁 Repository Structure

```text
GOODCABS-Transportation-and-Mobility-Project/
│
├── README.md
├── Dataset/
│   ├── fact_trips.csv
│   ├── fact_passenger_summary.csv
│   ├── dim_city.csv
│   ├── dim_date.csv
│   ├── dim_repeat_trip_distribution.csv
│   ├── monthly_target_trips.csv
│   ├── monthly_target_new_passengers.csv
│   └── city_target_passenger_rating.csv
│
├── SQL/
│   └── Ad-hoc business queries
│
└── Dashboard/
    └── Dashboard screenshots or files
```

*Note: Add the SQL and Dashboard folders only if you upload those files. Update the structure to match your actual repository.*

## 👨‍💻 Skills Demonstrated

SQL | Microsoft Excel | Data Analysis | KPI Tracking | Target vs. Actual Analysis | Customer Retention Analysis | Business Reporting | Data-Driven Decision Making
