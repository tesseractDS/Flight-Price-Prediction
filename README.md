✈️ Flight Price Prediction
-->Overview

This project focuses on Exploratory Data Analysis (EDA) and Feature Engineering for a Flight Price Prediction dataset.
The goal is to clean and preprocess flight data to prepare it for Machine Learning models that can accurately predict flight prices based on various features such as departure time, route, stops, airline, and more.

-->Objectives

Perform thorough data cleaning and handle missing values.

Extract useful time-based features from date and time columns.

Convert categorical data into numerical form for ML compatibility.

Derive new meaningful features such as Computed Stops, Duration (in minutes), and Route segments.

Prepare a clean dataset ready for model training.

-->Dataset Description

The dataset contains flight-related information such as:

Airline -->	Name of the airline
Date_of_Journey -->	Date of the flight
Source --> Starting location
Destination -->	Arrival location
Route	Flight path --> (eg DEL → BOM → COK)
Dep_Time -->	Time of departure
Arrival_Time	--> Time of arrival (may include next day info)
Duration	--> Total travel time (eg 2h 50m)
Total_Stops -->	Number of stops between source and destination
Price	Ticket --> price (target variable)
