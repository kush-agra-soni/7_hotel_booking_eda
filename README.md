# Hotel Booking EDA

## Overview
This project involves exploratory data analysis (EDA) on the `hotel_booking_eda` dataset. The primary goal is to analyze trends, patterns, and insights related to hotel bookings, cancellations, customer behavior, and other associated features.

## Dataset Information
- **Total Entries**: 119,390
- **Total Columns**: 32

### Column Details
1. `hotel` (object): Type of hotel (e.g., City Hotel, Resort Hotel).
2. `is_canceled` (int): Indicates if the booking was canceled (1) or not (0).
3. `lead_time` (int): Days between booking and arrival.
4. `arrival_date_year` (int): Year of arrival.
5. `arrival_date_month` (object): Month of arrival.
6. `arrival_date_week_number` (int): Week number of arrival.
7. `arrival_date_day_of_month` (int): Day of the month for arrival.
8. `stays_in_weekend_nights` (int): Number of weekend nights booked.
9. `stays_in_week_nights` (int): Number of weekday nights booked.
10. `adults` (int): Number of adults.
11. `children` (float): Number of children (may contain missing values).
12. `babies` (int): Number of babies.
13. `meal` (object): Type of meal plan.
14. `country` (object): Country of origin (may contain missing values).
15. `market_segment` (object): Market segment designation.
16. `distribution_channel` (object): Booking distribution channel.
17. `is_repeated_guest` (int): Indicates if the guest is a repeat visitor (1) or not (0).
18. `previous_cancellations` (int): Number of previous cancellations.
19. `previous_bookings_not_canceled` (int): Number of previous bookings not canceled.
20. `reserved_room_type` (object): Code for the reserved room type.
21. `assigned_room_type` (object): Code for the assigned room type.
22. `booking_changes` (int): Number of booking changes made.
23. `deposit_type` (object): Type of deposit paid.
24. `agent` (float): ID of the travel agent (may contain missing values).
25. `company` (float): ID of the company (significant missing values).
26. `days_in_waiting_list` (int): Days the booking was on the waiting list.
27. `customer_type` (object): Type of customer (e.g., transient, group).
28. `adr` (float): Average daily rate per room.
29. `required_car_parking_spaces` (int): Number of parking spaces required.
30. `total_of_special_requests` (int): Total number of special requests.
31. `reservation_status` (object): Status of the reservation (e.g., Check-Out, Canceled).
32. `reservation_status_date` (object): Date of the reservation status.

### Missing Values
- **`children`**: 4 missing values.
- **`country`**: 488 missing values.
- **`agent`**: 16,340 missing values.
- **`company`**: 112,593 missing values (significant).

## Objectives
1. Understand booking behaviors and trends.
2. Identify factors affecting cancellations.
3. Analyze customer demographics and preferences.
4. Derive actionable insights for decision-making.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (if predictive analysis is performed)

## Steps
1. Data Cleaning and Preprocessing:
   - Handle missing values.
   - Standardize data types.
2. Exploratory Data Analysis:
   - Univariate and bivariate analysis.
   - Visualizations for better insights.
3. Insights and Recommendations:
   - Summarize findings and actionable insights.

## Project Status
Final: Completed.
