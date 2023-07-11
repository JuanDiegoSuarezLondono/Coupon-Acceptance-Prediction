# Will a Customer Accept the Coupon?
This project aims to analyze the factors that determine whether a driver will accept a coupon delivered to their cell phone while driving. The goal is to use visualizations and probability distributions to distinguish between customers who accepted the coupon and those who did not. The data used for this analysis was collected through a survey on Amazon Mechanical Turk and is available in the UCI Machine Learning repository.

## Project Overview
The project involves exploring the survey data and identifying patterns and correlations related to customer acceptance of coupons. The analysis will include plotting, statistical summaries, and visualizations using Python. The findings will be compiled into a brief report, which will serve as the first portfolio piece, and will be published in a public GitHub repository.

## Data Description
The dataset contains various attributes related to users, contextual factors, and coupon attributes. The attributes include:

1. User attributes:
   - Gender: male or female
   - Age: below 21, 21 to 25, 26 to 30, and so on
   - Marital Status: single, married partner, unmarried partner, or widowed
   - Number of children: 0, 1, or more than 1
   - Education: high school, bachelor's degree, associate's degree, or graduate degree
   - Occupation: various categories such as architecture & engineering, business & financial, etc.
   - Annual income: different income ranges
   - Frequency of going to a bar, buying takeaway food, going to a coffee house, and eating at a restaurant with an average expense less than $20 per person

2. Contextual attributes:
   - Driving destination: home, work, or no urgent destination
   - Location of user, coupon, and destination: geographical information with distances and driving times
   - Weather: sunny, rainy, or snowy
   - Temperature: temperature ranges
   - Time: different time slots such as 10 AM, 2 PM, or 6 PM
   - Passenger: alone, partner, kid(s), or friend(s)
     
3. Coupon attributes:
   - Time before it expires: 2 hours or one day
   - 
## Deliverables
The deliverables for this project include:

1. Exploratory data analysis: Use Python to analyze and visualize the data, exploring the differences between customers who accepted the coupons and those who did not.
2. Report: Compile the findings into a brief report highlighting the key differences and correlations identified in the analysis.
3. GitHub repository: Publish the report and relevant code in a public GitHub repository, which will serve as the first portfolio piece.

## Conclusion
Based on the analysis conducted on different coupon types, certain conclusions can be drawn for each category. For example:

- Bar Coupons: Regular visitors to bars, aged below 30, and not accompanied by children are more likely to accept bar coupons.
- Time of Acceptance: The hours between 10 AM and 6 PM have the highest availability for accepting coupons.
- Weather Impact: Sunny days have a higher acceptance rate compared to other weather conditions.
- Traffic Flow: Sunny days attract more traffic from drivers.
- Carry Out & Take Away Coupons: Customers who are not in a hurry or going home, do not have children, and have occupations such as Construction & Extraction, Protective Service, or Building & Grounds Cleaning & Maintenance are more likely to accept these coupons.
- Coffee House Coupons: Customers who are not in a rush, have either a friend or partner as a passenger, and visit coffee houses more than 1 to 3 times a month are more likely to accept these coupons.
- Restaurant (< $20) Coupons: Customers who are not in a rush, not traveling alone, have a coupon expiring in one day, and are in the time range of 2 PM to 6 PM are more likely to accept these coupons.
- Restaurant (< $50) Coupons: Customers who have occupations in Protective Service, Construction & Extraction, or Life Physical Social Science fields, are not traveling alone, have a coupon expiring in one day, and are in the time range of 2 PM to 10 AM are more likely to accept these coupons.

The analysis provides valuable insights into customer behavior and preferences regarding coupon acceptance in various driving scenarios.
