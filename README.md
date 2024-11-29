![Britishairways](https://github.com/richardmukechiwa/British-Airways-Data-Analysis/blob/main/arkin-si-jDfvI6UOIeI-unsplash.jpg)
Photo by <a href="https://unsplash.com/@arkviation?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Arkin Si</a> on <a href="https://unsplash.com/photos/white-and-red-air-plane-in-mid-air-under-blue-sky-during-daytime-jDfvI6UOIeI?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
      

British Airways Service Delivery Analysis
Overview
The British Airways Service Delivery Analysis project aims to provide insights into customer satisfaction and service quality to help British Airways improve its service delivery and maintain its status as the airline of choice. By analyzing reviews and ratings from passengers, the airline can identify key areas for improvement and leverage its strengths to enhance customer experience.

Objectives
The main goals of this project are:

Assess the performance of British Airways across various service categories.
Identify trends and patterns in customer satisfaction over time.
Pinpoint specific areas for improvement, such as inflight entertainment or food services.
Provide actionable insights based on customer feedback to drive better service quality.
Dataset
The dataset was sourced from Kaggle and contains reviews of British Airways services, with the following key attributes:

Type of Traveller: (e.g., Solo Leisure, Couple Leisure)
Seat Type: (e.g., Economy, Business Class)
Route: Routes flown by passengers.
Ratings: Scores for seat comfort, cabin staff service, food & beverages, inflight entertainment, ground service, and value for money.
Recommended: Whether the customer would recommend the airline or not.
Dataset Details
Total records: 3,815 (reduced to 1,817 after cleaning and removing missing/duplicate values).
Columns after cleaning: 14 features, including a newly created overall_rating column.
Data Cleaning and Preparation
Missing Values
Columns with significant missing values, such as Wifi_&_Connectivity (83%) and Aircraft (48%), were dropped to ensure data reliability. Rows with null values in essential columns were also removed.

Duplicates
Duplicate records: 3
These were removed to maintain the integrity of the dataset.
Feature Engineering
Date_Flown: Converted to datetime format for trend analysis.
Overall_Rating: Created by averaging customer ratings across all service categories to represent overall satisfaction.
Final Dataset
The cleaned dataset comprises 1,817 records and includes key features such as:

Customer demographics and preferences: Type of Traveller, Seat Type.
Flight details: Route, Date Flown.
Service ratings: Seat Comfort, Cabin Staff Service, Food & Beverages, Inflight Entertainment, Ground Service, and Value for Money.
Exploratory Data Analysis (EDA)
Key insights from the EDA include:

Overall Satisfaction: The average overall_rating is 3.2/5, indicating moderate customer satisfaction.
High-performing areas: Cabin staff service received the highest average rating of 3.2/5, followed by seat comfort at 2.8/5.
Low-performing areas: Inflight entertainment and food & beverages scored lower, with averages of 2.6/5 and 2.6/5, respectively.
Recommendations: Around 60% of passengers recommended British Airways to others.
Visualizations
Distribution of Overall Ratings: A histogram showing customer satisfaction distribution.
Service Category Performance: A bar chart comparing average scores across service categories.
Trends Over Time: A line plot showing variations in overall satisfaction across different months.
Key Insights
Strengths:

Cabin staff service is a major strength, with relatively high ratings across all types of travelers.
Passengers in business class generally have higher overall satisfaction compared to economy class.
Areas for Improvement:

Inflight entertainment and food & beverages need significant attention, as they consistently score below average.
Solo leisure travelers report lower satisfaction compared to other traveler types.
Frequent Comments:

Positive: Professionalism of cabin staff, smooth boarding process.
Negative: Limited meal options, outdated inflight entertainment systems.
Recommendations
Enhance inflight entertainment:
Upgrade the system to offer a wider selection of movies, music, and games.
Improve meal quality:
Introduce diverse menu options to cater to different tastes and dietary preferences.
Customer engagement:
Gather real-time feedback from passengers to address concerns promptly.
Focus on value for money:
Provide more transparent pricing and perks for economy-class travelers.
Tools and Libraries
Libraries Used: pandas, numpy, matplotlib, seaborn, plotly.
Visualization Tools: Seaborn and Plotly for creating insightful plots and dashboards.
Conclusion
This project provides a comprehensive analysis of British Airways' service delivery, helping the airline understand its strengths and areas of improvement. By acting on these insights, British Airways can enhance its reputation and deliver an exceptional travel experience to its customers.

