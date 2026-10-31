# Hotel_Operations_Python-EDA_Project
# 1. Project Overview

This project analyses hotel booking records for Elite Hotels International to understand booking behaviour, cancellation patterns, guest preferences and revenue-related indicators. The objective is to turn booking data into practical insights that can support operational planning, customer experience and revenue management.

The analysis covers both City Hotel and Resort Hotel bookings and includes basic, intermediate and advanced-level questions.

# 2. Business requirements
• Understand booking lead time, arrival dates and stay duration.

• Compare City Hotel and Resort Hotel bookings.

• Measure cancellations and identify related booking characteristics.

• Analyse guest demographics, booking channels and room preferences.

• Study ADR, seasonal demand and special requests.

• Provide practical recommendations for hotel management.

# 3. Tools and technologies
• Python: analysis language.

• Jupyter Notebook: code execution and documentation.

• Pandas: cleaning, grouping, filtering and aggregation.

• NumPy: numerical operations.

• Matplotlib and Seaborn: data visualisation.

# 4. Challenges faced
• Large number of exact duplicate records.

• Missing values in guest and booking metadata.

• Separate arrival date components requiring date construction.

• Mixed numerical and categorical features for machine learning.

• Cancellation-class prediction required more than accuracy-only evaluation.

• ADR and revenue interpretation needed care because ADR alone is not total revenue.

# 5. Key findings – booking and guest behaviour
• Average lead time: 79.89 days

• Canceled bookings: 24,025

• Most common arrival month: August (11,257 bookings)

• Most frequent country code:	PRT (27,453)

• Average special requests:	0.699 per booking

• Average total stay:	3.63 nights

• Bookings with agent ID recorded: 103,050

• Most booked reserved room type:	A (56,552)

# 6. Key findings – cancellations and revenue indicators
• City Hotel cancellation rate:	30.04%

• Resort Hotel cancellation rate:	23.48%

• Lead-time / cancellation correlation:	0.185

• Cancellation rate, 0–7 day lead time:	8.43%

• Cancellation rate, 365+ day lead time: 40.88%

• Average ADR – City Hotel:	110.99

• Average ADR – Resort Hotel:	99.03

• Highest-volume distribution channel: TA/TO (69,141 bookings)

• Highest booking market segment:	Online TA (51,618)

# 7. Business recommendations
• Review longer-lead-time bookings and consider suitable confirmation or deposit policies.

• Investigate why City Hotel cancellations are higher than Resort Hotel cancellations.

• Use monthly demand patterns to plan staffing, room readiness and inventory.

• Track ADR and cancellation rates by hotel type, market segment and booking channel.

• Use guest special requests to improve service preparation.

• Use cancellation model scores only to prioritise manual review, not to automatically reject bookings.

• Compare new and repeat guest patterns when designing loyalty initiatives.
