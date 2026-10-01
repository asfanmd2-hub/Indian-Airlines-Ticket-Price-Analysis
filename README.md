
# Indian Airlines Ticket Price Analysis

## Objective

As someone interested in aviation and travel, I have always been curious about how airline ticket prices change depending on different factors. The aviation industry experienced a major decline during the Covid-19 pandemic, followed by a gradual recovery. At the same time, factors such as the Russia–Ukraine war and increasing Aviation Turbine Fuel (ATF) prices contributed to a significant rise in airfares.

To understand these price variations better, I conducted an Exploratory Data Analysis (EDA) on airline ticket prices in India. The main purpose of this project was to identify the factors influencing flight ticket prices and understand patterns in flight availability and pricing.

Some of the key questions explored in this analysis include:
- How many flights are available across different cities in India?
- How does ticket availability vary between Economy and Business classes?
- What is the price range for different travel classes?
- How do factors such as stops, duration, departure time, and days left affect ticket prices?



## About the Dataset

The dataset used in this project was obtained from Kaggle and is considered secondary data. It contains information about flight booking options available through the "EaseMyTrip" website for journeys between six major metropolitan cities in India.

After cleaning and preprocessing, the dataset consisted of **300,261 records and 11 features**. The data was collected separately for Economy and Business class tickets.

The dataset contains flight booking information collected over a period of 50 days, from **February 11, 2022, to March 31, 2022**. In total, the website provided 300,261 unique flight booking combinations.

**Dataset:** [Kaggle]

### Features in the Dataset

1. **Airline:** Represents the airline operating the flight. The dataset contains six different airlines and this is a categorical variable.

2. **Flight:** Contains the unique flight code or flight number associated with each journey.

3. **Source City:** Represents the city from which the flight begins. There are six different source cities in the dataset.

4. **Departure Time:** Represents the approximate departure period of the flight. The actual departure times are grouped into six different time categories.

5. **Stops:** Indicates the number of stops or layovers between the source and destination. It contains three different categories.

6. **Arrival Time:** Represents the approximate time period when the flight reaches its destination. Arrival times are grouped into six different categories.

7. **Destination City:** Indicates the city where the flight ends. The dataset contains six different destination cities.

8. **Class:** Represents the travel class selected by the passenger, such as Economy or Business.

9. **Duration:** Indicates the total amount of time required to complete the journey between the source and destination cities.

10. **Days Left:** Represents the number of days between the booking date and the actual date of travel.

11. **Price:** Represents the ticket fare and serves as the target variable for the analysis.

## Power BI Visualization Dashboard

A Power BI dashboard was created to present the findings in an interactive and easy-to-understand format.



The dashboard provides a quick overview of ticket prices between different cities and allows users to compare airlines, travel classes, flight durations, and other important factors affecting airfare.

## Conclusion

The analysis produced several interesting observations regarding airline ticket prices in India:

1. **Economy vs. Business Class:** Air Asia had the lowest-priced tickets in the Economy category, while Air India offered the lowest prices among Business class flights.

2. **Booking Time:** Tickets booked around 3–7 weeks before the journey were generally more affordable than tickets purchased within three weeks of departure. Prices tended to increase significantly during the final 2–20 days before travel. Although tickets could sometimes be inexpensive one day before departure, booking several weeks in advance generally provided better prices.

3. **Flight Duration:** Ticket prices generally increased as flight duration increased, reaching a peak around 20 hours. For flights exceeding 20 hours, some outliers caused prices to decrease again. Overall, the relationship between duration and price can be approximated using a second-degree curve.

4. **Departure and Arrival Time:** Flights departing late at night and arriving either early in the morning or late at night generally had lower ticket prices.

5. **Number of Stops:** Ticket prices tended to increase as the number of stops increased.

6. **City-wise Pricing:** Delhi had the lowest average flight prices among the cities analyzed, whereas Hyderabad had the highest.
