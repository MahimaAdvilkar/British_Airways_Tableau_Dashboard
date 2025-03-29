British Airways Tableau Dashboard
This repository contains a Tableau dashboard that visualizes customer reviews and performance metrics for British Airways. The dashboard presents an in-depth analysis of various airline service attributes such as cabin staff service, food and beverages, seat comfort, and overall value for money, among others. The visualizations aim to help stakeholders understand customer satisfaction trends and identify areas for operational improvements.

Dashboard Overview
Key Features:
Interactive Filters: Users can filter data by various attributes such as travel type, seat type, and aircraft.

Metrics Visualization: Displays average ratings for key metrics like cabin staff service, seat comfort, food, and overall value for money.

Trend Analysis: Visualize trends over time, such as seat comfort ratings by month.

Geospatial Insights: Average seat comfort ratings displayed on a map, providing a geographic view of customer satisfaction.

Aircraft Performance: Analyze customer reviews across different aircraft types and models.

Key Insights:
Average Ratings:

Overall Rating: 4.2 (out of 5), indicating a generally positive customer experience with British Airways.

Cabin Staff Service: 2.8, suggesting room for improvement in customer service quality, with a focus on staff interactions.

Seat Comfort: 2.4, indicating that passengers find seat comfort to be suboptimal, which could be a key area for improvement.

Entertainment: 1.1, highlighting that entertainment options are considered the weakest aspect of the service.

Food and Beverages: 1.9, showing that passengers rate food and beverages poorly, signaling a potential area for improvement.

Ground Service: 2.6, indicating that ground services could benefit from attention, although it is better than the food and entertainment ratings.

Value for Money: 2.2, indicating that passengers feel the value for money does not meet expectations.

Seat Comfort by Month:

The seat comfort ratings show fluctuating trends over the years with noticeable spikes and dips, suggesting varying customer satisfaction levels over time. A noticeable increase in ratings was observed around 2023, indicating potential improvements made in seating or perceived comfort.

Seat Comfort by Country:

The map shows average seat comfort ratings across different countries. Countries such as the US and Canada have higher ratings, indicating relatively better customer satisfaction with seat comfort, while regions like Asia and Europe show lower scores.

Seat Comfort by Aircraft:

Different aircraft models have varying seat comfort ratings:

Boeing 747: 2.0, rated the highest among major aircraft, but still under 3, indicating average satisfaction.

Boeing 787-9: 1.5, showing that this aircraft model is less favored by passengers when it comes to seat comfort.

Boeing 777: 1.7, again a lower score, highlighting potential issues with the seating arrangement on this aircraft type.

A380: 2.2, providing a more comfortable experience, but still in need of improvement.

Data Insights:
Aircraft Comparison: Review customer ratings for different aircraft models.

Customer Type: Compare reviews based on traveller type (business, solo, family, etc.).

Business Travelers generally rate seat comfort and cabin staff service higher than leisure travelers.

Solo Leisure Travelers tend to rate the food and entertainment more negatively than other traveler types.

Trend Analysis:

Seat Comfort has remained relatively stagnant over the years, indicating a lack of significant improvements in this area.

Cabin Staff Service saw some fluctuations with noticeable drops in 2020, likely due to pandemic-related factors affecting customer service standards.

Screenshots:

Data
The dataset used for this project includes:

BA Reviews Data: Contains customer reviews and ratings for various service metrics like seat comfort, food, and cabin service.

Countries Data: Provides geographic data for visualizing review data by country.

File Structure:
kotlin
Copy
british-airways-tableau-dashboard/
├── README.md
├── British_Airways_Dashboard.twbx (Tableau Workbook)
├── ba_reviews.csv (Customer reviews data)
├── Countries.csv (Geographic data)
└── Dashboard 1.png (Dashboard Screenshot)
Requirements
Tableau Desktop (or Tableau Public) to open the .twbx file.

An internet connection to view the Tableau Public dashboard online.

How to Use
Clone or download this repository.

Open the Tableau workbook British_Airways_Dashboard.twbx with Tableau Desktop or Tableau Public.

Interact with the dashboard by applying filters and exploring different views.

View the Dashboard
Check out the interactive Tableau dashboard online: British Airways Tableau Dashboard

License
This project is licensed under the MIT License - see the LICENSE file for details.
