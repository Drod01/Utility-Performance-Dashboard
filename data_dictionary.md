
# Data Dictionary for Utility Performance Dashboard

## 1. energy_consumption.csv
| Column Name        | Data Type | Description |
|--------------------|-----------|-------------|
| Date               | String    | Month and year in YYYY-MM format |
| Region             | String    | Geographical region (e.g., North, South) |
| Consumption_kWh    | Integer   | Total energy consumption in kilowatt-hours for the month and region |

## 2. outages.csv
| Column Name            | Data Type | Description |
|------------------------|-----------|-------------|
| Date                   | Date      | Date of outage event in YYYY-MM-DD format |
| Region                 | String    | Geographical region |
| Outage_Duration_Minutes| Integer   | Duration of outage in minutes |
| Customers_Affected     | Integer   | Number of customers affected by the outage |

## 3. customer_satisfaction.csv
| Column Name         | Data Type | Description |
|---------------------|-----------|-------------|
| Date                | String    | Month and year in YYYY-MM format |
| Region              | String    | Geographical region |
| Satisfaction_Score  | Float     | Average customer satisfaction score (1.0 to 5.0) |
