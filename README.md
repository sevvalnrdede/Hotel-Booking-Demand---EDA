Hotel Booking Demand - Exploratory Data Analysis (EDA)
Introduction
In the hotel industry, understanding customer behavior is a key factor for success. Booking cancellations directly impact revenue management and room occupancy planning. This project performs a deep dive into a hotel booking dataset to uncover the patterns and factors that influence a guest's decision to stay or cancel.

Project Objectives:
Exploration: Analyze the differences between City Hotels and Resort Hotels.
Analysis: Identify key variables (Lead Time, Deposit Type, Special Requests) that correlate with cancellations.
Feature Engineering: Create new metrics like total_stay and is_local to gain deeper behavioral insights.
Actionable Insights: Provide data-driven recommendations for hotel management to optimize booking stability.

Dataset Overview
Size: Approximately 119,000 booking records.
Features: 32 variables including customer demographics, length of stay, and booking channels.
Status: Data has been cleaned, missing values handled, and new features engineered for better analysis.

Key Insights & Conclusion
After a thorough Exploratory Data Analysis, we have reached the following strategic conclusions:
Lead Time Sensitivity: There is a clear positive correlation (approx. 0.29) between lead time and cancellations. The earlier a guest books, the higher the risk of them canceling. Management should consider stricter policies for long-term bookings.
Commitment Signals: * Parking: Guests who request a parking space have a nearly 0% cancellation rate.
Special Requests: As the number of special requests increases, the cancellation rate decreases. Engaged customers are more likely to arrive.
Local vs. International Market: Local guests (from Portugal) show different cancellation patterns than international tourists. This insight allows for region-specific marketing and cancellation strategies.
The Deposit Paradox: Interestingly, 'Non-Refund' deposit types show a high cancellation rate in this specific dataset. This suggests that these bookings might belong to higher-risk segments that need closer monitoring.
Pricing (ADR): Higher average daily rates (ADR) are slightly more common in canceled bookings, suggesting price sensitivity plays a role in the decision-making process.
Final Verdict: To minimize revenue loss, hotels should focus on guests who show "commitment signals" (like special requests) and apply dynamic deposit policies for bookings with very long lead times.

Tools & Technologies
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Environment: Jupyter Notebook
