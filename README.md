# ⭐ Booking & Payment Analytics Dashboard for Financial Reporting
This project delivers an end-to-end Booking & Payment Analytics Dashboard designed to provide finance and operational teams with real-time visibility into booking volumes, payment performance, and revenue trends.
The dashboard consolidates transactional data into a single analytical view, automating reporting processes and enabling faster business decision-making.

# 🚀 Project Overview
Traditional booking and payment analysis relied heavily on manual spreadsheets, resulting in delayed insights and inconsistent financial reporting.
This dashboard solves these issues by integrating SQL-based data extraction, structured data modeling, and automated visualization in Looker Studio.

The result:

-  Centralized KPI monitoring
-  Cleaner, validated transactional data
-  Automated daily reporting
-  Faster identification of anomalies and payment failures


# 🎯 Objectives

- Build a unified analytics dashboard for bookings and payments
- Automate recurring financial reporting
- Improve data accuracy and reduce manual spreadsheet work
- Identify patterns in revenue, booking trends, and payment behavior
- Support management with actionable and real-time insight

# 📚 Dataset Description
| Column Name     | Description                                                                                                            |
| --------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **addssr**      | Additional services purchased (e.g., baggage, meal, seat). Indicates whether extra services were added to the booking. |
| **bank**        | The bank or payment provider used for the transaction.                                                                 |
| **booking**     | Booking identifier or booking count associated with the record.                                                        |
| **channel**     | Source of the booking (e.g., Mobile App, Website, Partner Channel).                                                    |
| **date**        | Transaction or booking date. Used for trend and time-series analysis.                                                  |
| **destination** | Arrival airport or final destination of the route.                                                                     |
| **eticket**     | E-ticket number associated with the booking.                                                                           |
| **origin**      | Departure airport or origin of the route.                                                                              |
| **paxtype**     | Passenger type (e.g., Adult, Child, Infant).                                                                           |
| **payment**     | Payment amount or indicator of successful payment (depending on data structure).                                       |
| **paymenttype** | Method used to pay (e.g., Virtual Account, Credit Card, E-Wallet).                                                     |
| **promocode**   | Promo code applied to the booking, if any.                                                                             |
| **revenue**     | Revenue generated from the booking or payment.                                                                         |
| **route**       | Complete flight route (e.g., CGK–DPS).                                                                                 |
| **ssrtype**     | Type of Special Service Request (e.g., extra baggage, wheelchair).                                                     |
| **USEPROMO**    | Indicates whether a promo was used (Yes/No or binary flag).                                                            |


# 📊 Dashboard Development (Looker Studio)

The dashboard includes:
Page 1 — BOOKING AND TICKETING
- Total Revenue
- Total Bookings
- Successful Payments
- Week-over-week Revenue Change

Page 2 — Payment Summary 
- Daily booking trends
- Booking value distribution

Channel contribution
# Projects
1. [IKN PROPERTY](https://github.com/FTDS-assignment-bay/p2-final-project-ftds-026-rmt-group-001/tree/main)
    - **Description:** The goal of this project is to make a prediction model that will tell users the prices of their house if the user were to sell their house or property in Ibukota Nusantara (IKN).
    - **Technologies Used:** The notebooks use Random Forest, Light GBM, XGBoost, Decision Tree, Lasso Regression, Gradient Boosting Regression.
    - **Results:** A regression model that can predict the house prices of IKN and its surrounding area. The model chosen was XGBoost with the final result of 83% R2 accuracy–with the lowest error margin of about 5%.
    - **Deployment:** Check huggingface page to real experience [here](https://huggingface.co/spaces/xyncz/IKN-Price-Prediction)
