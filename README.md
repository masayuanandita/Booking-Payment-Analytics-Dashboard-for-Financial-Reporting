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
This page focuses on understanding booking patterns, route performance, ancillary service behavior, and overall transaction volume.

Primary Insights
- Booking distribution between Domestic (50.31%) and International (49.69%) is well-balanced.
- 59.83% of bookings include SSR, indicating strong ancillary revenue potential.
- Seat selection and baggage are the top SSR contributors, supporting upsell strategies.
- Monthly booking trends show clear seasonality, useful for forecasting and resource planning.

Page 2 — Payment Summary 
This provides financial visibility into payment activity, promo effectiveness, bank performance, and payment method usage. 

Primary Insights
- Several promo codes contribute significantly to transaction volume, with GOTF leading at 170 rb.
- Daily payment activity shows high variability, useful for detecting payment system anomalies or traffic peaks.
- Bank Transfer and Credit/Debit Cards are the most frequently used payment methods.
- High bank segmentation allows identification of bank-level issues or settlements delays.
- Payment revenue reaches 2.1 T, confirming the business scale and demand consistency.

🔗 Dashboard
[https://lookerstudio.google.com/reporting/0176be82-8db4-4ac7-823e-daa84fe59774]
