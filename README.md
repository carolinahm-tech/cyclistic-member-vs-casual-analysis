# Cyclistic Member vs Casual Analysis

## Business Context

Cyclistic is a bike-sharing company seeking to convert casual riders into annual members. Understanding behavioral differences between both user segments is critical to designing effective marketing strategies.

---

## Objective

Identify behavioral patterns between annual members and casual riders in order to support data-driven strategic decisions.

---

## Data Source

- Public Cyclistic dataset
- Data processed using SQL (Google BigQuery)
- Visualization built in Power BI

---

## Process

1. Data cleaning and transformation in BigQuery.
2. Aggregation by:
   - User type (member vs casual)
   - Weekday
   - Hour of day
   - Month
3. Creation of structured analytical tables.
4. Dashboard design in Power BI following consistent visual hierarchy principles.

---

## Key Insights

### User Behavior Patterns
- Annual members generate significantly more total rides than casual riders.
- Members demonstrate strong weekday consistency, especially mid-week.
- Casual riders increase activity toward weekends.
- Hourly patterns suggest commuting behavior for members.

### Seasonal Dynamics
- Ridership peaks during summer months.
- Casual rider activity increases more noticeably in warmer months.
- Members maintain relatively stronger consistency throughout the year.
- Demand declines in colder months across both segments.

---

## Strategic Recommendations

- Focus marketing campaigns on converting high-season casual riders into annual members.
- Promote weekday commuting benefits to reinforce member value proposition.
- Launch seasonal subscription incentives before peak summer demand.
- Implement targeted weekend promotions to attract and convert casual riders.

---

## Dashboard Preview

### 1️⃣ Total Rides & Ratio
![Total Rides](page1_total_rides.png)

### 2️⃣ Weekly Distribution
![Weekday Analysis](page2_weekday.png)

### 3️⃣ Hourly Distribution
![Hourly Analysis](page3_hour.png)

### 4️⃣ Monthly Seasonality
![Monthly Analysis](page4_month.png)

### 5️⃣ Business Insights
![Business Insights](page5_insights.png)

---

## Tools Used

- SQL (Google BigQuery)
- Power BI
- GitHub
