# New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python
---

> Author: Richard Taracha

> Date: 08/11/2020

![NYC Home Page Image](https://user-images.githubusercontent.com/67068918/98472046-59182b80-2201-11eb-940d-b18f930166e8.png)

---

### Table of Contents
Sections headers used to reference locations of each destination:

- [External Data Source Validation](#external-data-source-validation)
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Recommendations](#recommendations)
- [Author Information](#author-information)

---

## External Data Source Validation

According to https://www.nycgo.com/neighborhoods-boroughs/about-nyc-five-boroughs/, New York City has 5 main Boroughs namely: the Bronx, Brooklyn, Manhattan, Queens and Staten Island—each with dozens of neighborhoods lending their own local flavor

Our data set contains these boroughs confirmed using the formular df.Boro.Unique(): New Jersey', 'Manhattan', 'Bronx', 'Westchester', 'Brooklyn', 'Rockland County', 'Nassau County', 'Queens', 'Staten Island', 'Connecticut', 'All Boroughs' which is more than what the information above has indicated although the data contains the 5 main boroughs. The assumption is that the extra boroughs are within the 5 main boroughs.

The data is provided to the NYC open data by Department of Education (DOE) and can be accessed via https://data.cityofnewyork.us/Transportation/Bus-Breakdown-and-Delays/ez4e-fazm

> All personally identifying information has been removed from the data.

## Understanding The Context

With this project, I'm working as a Data Science Consultant and has been tasked to provide recommendations on how to reduce the cases of breakdown of buses in the city of New York. 

Given a dataset, I performed data exploration and data wrangling (data cleaning and analysis) then came up with some appropriate recommendations. 

#### Technologies and Tools

- Pandas
- Namupy

[Back To The Top](#Hilton-International-Hotels-Booking-Visualisations)

---

## Project Deliverable
Deliverable is a python notebook that contains my solution:

* Notebook name: Hilton International Hotels Booking Visualisations.ipynb

Dataset Overview:
The dataset that was provided comes from the Bus Breakdown and Delay system which collects information from school bus vendors operating out in the field in real time. Bus staff that encounter delays during the route are instructed to radio the dispatcher at the bus vendor’s central office. The bus vendor staff are then instructed to log into the Bus Breakdown and Delay system to record the event and notify OPT. OPT customer service agents use this system to inform parents who call with questions regarding bus service. The Bus Breakdown and Delay system is publicly accessible and contains real time updates. All information in the system is entered by school bus vendor staff.

* Dataset name: hotel_bookings.csv
* Dataset Download Link: https://bit.ly/2WvQbhJ

[Back To The Top](#Hilton-International-Hotels-Booking-Visualisations)

---

## Recording the Experimental Design
1. Define the Research Question
2. Data Importation
3. Data Exploration
4. Data Cleaning
5. Data Preparation
6. Data Analysis

Given the dataset, I performed data exploration, data wrangling (cleaning and analysis) in an effort to come with appropriate recommendations. 

As a start while performing data analysis, I derived the following questions from the given dataset: 
1. Which bus companies that had the highest breakdowns?
2. What were the top 3 reasons for bus delays?
3. How many students were in the buses when they broke down?
4. Which were most frequent reasons for bus breakdowns?
5. What were the most frequent reasons for the bus running late?
6. What was the average delay time of each reason type?


[Back To The Top](#Hilton-International-Hotels-Booking-Visualisations)

---

## Summary Of Findings

Below are some of the findings derived from the dataset and visually represented:

#### Lineplot showing Monthly Booking Trend by City Hotel and Resort Hotel
![monthly_booking_trend_city_resort_line_graph](https://user-images.githubusercontent.com/67068918/93030105-36b2c900-f629-11ea-94a5-35ad4d4d6136.png)

#### Lineplot showing Monthly Booking Trend
![monthly_booking_trend_line_graph](https://user-images.githubusercontent.com/67068918/93030138-77124700-f629-11ea-9d38-09ab47470f9c.png)

#### Bar and Pie Charts showing the percentage number of bookings cancelled 
![percentage_bookings_cancelled](https://user-images.githubusercontent.com/67068918/93030157-9a3cf680-f629-11ea-97ce-2d7dba443d81.png)

#### Bar Chart Showing the Percentage Booking Per Year By Hotel(City/Resort)
![percentage_booking_per_year_by_hotel](https://user-images.githubusercontent.com/67068918/93030324-cdcc5080-f62a-11ea-95c5-ef852e6f1d55.png)

[Back To The Top](#Hilton-International-Hotels-Booking-Visualisations)

---

## Recommendations

From the above analysis, below are our recommendations:

* Both City Hotels and Resort Hotels should come up with new marketing strategies or improve on already existing ones to cleary advertise on their presence, communicate on the services they offer, deals if any in order to improve on the number of bookings.

* We can see that bookings have increased over the years and inorder to maintain this trend, the hotels can offer special deals/ rates especially during off-peak periods. This will attract more customers and in turn increase the number of bookings hnce and increase in revenue.

* August is one of the busiest months for the Hotel industry. As mentioned earlier the hotels can opt to introduce incentives for any making abooking during the less busier months like January that has a Booking Rate of less than 5%

* To increase on the number of guests coming from different countries, the hotel management may opt to introduce referral programs where a previous guest may get discount rates on their next booking if they reffered someone else who then indeed made a booking.

* To increase on the total number of nights spent at a hotel, management may also opt to add an extra free night for guests who book for 4 or more nights as a perk.

* As noted most bookings are made by couples. The hotel may introduce more family friendly services and activities e.g a playground for children may increase the bookings made by a family.

[Back To The Top](#Hilton-International-Hotels-Booking-Visualisations)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#Hilton-International-Hotels-Booking-Visualisations)


