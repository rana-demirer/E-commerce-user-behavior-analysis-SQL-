# E-commerce-user-behavior-analysis-SQL-
Developed a PostgreSQL-based summary using CTEs, Joins and aggregations to analyze e-commerce behavior providing data driven recommendations 

***! ! ! Please review: Codes are provided in the [SQL Codes](https://github.com/developerRD/E-commerce-user-behavior-analysis-SQL-/blob/main/SQL%20codes) folder

This project uses a Kaggle dataset to simulate a real-world e-commerce environment. The goal was to move beyond basic reporting and provide actionable recommendations to answer critical business questions, such as:

* Which channels are underperforming despite high traffic?

* Is there a significant "drop-off" between adding an item to the cart and completing a purchase?

* How do user engagement metrics (time on site, pages viewed) translate into actual revenue?

| Column  | Purpose in Analysis |
| ------------- | ------------- |
| session_id  | Used as the primary key to count unique visits |
| traffic_source  | Essential for calculating ROI and channel efficiency. |
| added_to_cart | purchased	Critical for Funnel Analysis and identifying "leaky" conversion stages. |
| pages_viewed |time_on_site	Measures User Engagement; helps distinguish "window shoppers" from "serious buyers." |
| device_type	Informs technical | Informs technical/UX recommendations (e.g., "Mobile vs. Desktop" performance). | 
| order_value_usd | The bottom-line metric for calculating Average Order Value (AOV) and Total Revenue. |

Link to dataset: https://www.kaggle.com/datasets/chaitanyajamble/global-e-commerce-user-behavior-and-conversion-data/data

#Methods Applied


# SQL Results

<img width="1194" height="229" alt="image" src="https://github.com/user-attachments/assets/a3543174-8c25-4392-bc71-4a0022e43f07" />

# These initial results suggest the points below
- Referral traffic is the highest in both total revenue, which is 13.6k and conversion 38% primarily by Mobile users. It  makes sense to focus on growing mobile referral channels.
- Improve organic search improve the likelihood that interested visitors complete a purchase.
- Desktop is the dominant device platform for almost all channnels meaning maintaining or improving a strong desktop checkout experience is essential for sustaining high revenue.
  
