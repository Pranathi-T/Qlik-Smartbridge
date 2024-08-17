# Exploring Insights From Synthetic Airline Data Analysis With Qlik

## Overview

This project aims to explore and analyze synthetic airline data using Qlik Sense, a powerful data visualization and business intelligence tool. The dataset simulates various aspects of airline operations, including flight schedules, passenger demographics, ticket sales, and performance metrics. The objective is to uncover patterns, trends, and correlations within the data to support strategic decision-making processes for airlines, airports, and related stakeholders.

## Project Objectives

The project is structured around three main objectives:

1. **Revenue Optimization**
   - Analyze historical ticket sales data to identify peak travel times, popular destinations, and effective pricing strategies.
   - Segment customers based on purchasing behavior to tailor marketing strategies and maximize profitability.

2. **Operational Efficiency**
   - Examine flight schedules, passenger flows, and luggage handling processes to enhance operational efficiency.
   - Identify bottlenecks in airport operations and propose strategies to optimize resource allocation.

3. **Customer Experience Enhancement**
   - Perform sentiment analysis on customer feedback to identify areas for service improvement.
   - Develop personalized offerings and targeted marketing campaigns to improve customer satisfaction and loyalty.

## Methodology

The analysis was conducted using Qlik Sense, following these key steps:

1. **Data Ingestion:** Loading and preparing the synthetic airline dataset in Qlik Sense.
2. **Data Exploration:** Utilizing Qlik’s associative model to explore relationships between different data fields.
3. **Data Cleaning:** Modifying and enhancing the dataset to include additional fields for a more in-depth analysis.
4. **Visualization:** Creating interactive dashboards to visualize key insights.
5. **Analysis:** Interpreting the visual data to derive actionable insights and recommendations.

## Dataset Overview

The dataset is a synthetic representation of airline operations, providing a rich and comprehensive view of various aspects, from passenger demographics to flight performance. The original dataset includes fields such as:

- Passenger ID
- First Name
- Last Name
- Gender
- Age
- Nationality
- Airport Name
- Airport Country Code
- Country Name
- Airport Continent
- Continents
- Departure Date
- Arrival Airport
- Pilot Name
- Flight Status

After data cleaning, additional fields were added to enhance the analysis, including:

- Nationality GeoInfo
- Airport Country Code GeoInfo
- Country Name GeoInfo
- Age Group
- Year (extracted from Departure Date)
- Month (extracted from Departure Date)

## Key Findings

The Overview of Passenger Statistics dashboard provides a highlevel summary of
essential passenger metrics, crucial for quickly assessing the airline’s overall performance. It
displays the total number of passengers, which helps gauge the scale of airline operations and
the volume of customer engagement. The gender distribution metric breaks down passengers
into male and female categories, offering insights into demographic trends and aiding in
targeted marketing strategies.
The flight status breakdown is particularly significant, categorizing flights into On Time,
Delayed, and Canceled. This visualization allows stakeholders to swiftly identify the proportion
of flights meeting performance standards versus those falling short. A high percentage of
delayed or canceled flights could signal operational inefficiencies or customer service issues,
necessitating immediate attention.
The InDepth Analysis of Flight Status and Demographics dashboard offers a detailed
examination of various aspects of airline performance and passenger characteristics. It tracks
flight status over a threemonth period, revealing trends in delays, cancellations, and ontime
arrivals. This temporal analysis helps identify patterns, such as recurring delays on specific
routes or during certain periods, enabling targeted interventions to improve punctuality.
Continental flight status distribution highlights regional performance variations, identifying
which continents experience higher rates of delays or cancellations.
This geographic insight can guide strategic decisions related to rou
## Dashboards

Two interactive dashboards were created to visualize the key insights:

1. **Dashboard 1:**
   - Total Number of Passengers
   - Number of Passengers by Gender
   - Number of On-Time Flights
   - Top 5 Number of Passengers Traveled (Month-wise)
![Screenshot 2024-08-12 110745](https://github.com/user-attachments/assets/b24ee15d-229b-49b4-a127-c5bd07ebbfe2)

2. **Dashboard 2:**
   - Top 3 Months Flight Status
   - Age Group & Gender-wise Passenger Distribution
   - Continent-wise Flight Status
   - Number of Passengers by Nationality
![Screenshot 2024-08-12 110834](https://github.com/user-attachments/assets/06c3245d-181a-4631-bee6-8323ab173ef3)


## Conclusion

The project successfully demonstrated how Qlik can be utilized to extract valuable insights from synthetic airline data, which can be used to drive strategic decisions in revenue optimization, operational efficiency, and customer experience enhancement. These insights provide a strong foundation for airlines, airports, and stakeholders to improve operations, increase profitability, and enhance customer satisfaction.

## Acknowledgements

- **Dataset:** The synthetic airline data was obtained from Kaggle.
- **Tool:** Qlik Sense was used for data visualization and analysis.
