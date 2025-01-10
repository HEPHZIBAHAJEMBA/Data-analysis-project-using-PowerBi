# Hotel revenue data analysis project

### Project overview
#### This dataset shows the analysis of a hotel revenue data.

### Data source
#### https://absentdata.com/data-analysis/... contains revenue data from the hotel

### Tools
- Excel-Data Cleaning
- SQL-Data Analysis
- Power Bi-Creating Report

### Data cleaning and Preparation
- Create a Database
- Query and analyze data with SQL
- Integrate Power BI with a Database
- Create Data Visualizations Using Power BI

 ### Exploratory Data Analysis (EDA)
- Is our hotel revenue growing yearly?
- Should we increase our parking lot size?
- What trends can we see in the data?
  
### Data analysis
   ```sql
   select 
arrival_date_year,
hotel,
sum((stays_in_week_nights + stays_in_weekend_nights)*adr) as Revenue
from hotels
group by arrival_date_year,hotel
```


