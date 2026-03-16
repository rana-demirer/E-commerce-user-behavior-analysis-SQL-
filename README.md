# E-commerce-user-behavior-analysis-SQL-
Developed a PostgreSQL-based summary using CTEs to analyze e-commerce behavior providing data driven recommendations 

Codes are provided in the SQL codes folder

This project uses a Kaggle dataset to simulate a real-world e-commerce environment. The goal was to move beyond basic reporting and provide actionable recommendations to answer critical business questions, such as:

* Which marketing channels are underperforming despite high traffic?

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
