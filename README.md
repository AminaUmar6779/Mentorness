# Cost of living Analysis

## Project Overview 
This project revolves around the analysis of the cost of living in various cities and countries across the
globe. The dataset used for this analysis encompasses a wide range of economic indicators, from the
price of basic commodities to the cost of housing, transportation, and even entertainment. By
harnessing the power of Power BI, we aim to gain valuable insights into the economic disparities
between different regions and understand the factors that contribute to the varying costs of living. This
project serves as an exercise in data visualization, analysis, and interpretation, offering a comprehensive
view of the world's economic landscape.

## Problem Statement

The cost of living is a crucial metric that impacts individuals and businesses alike. Understanding the cost
of living in different cities and countries is vital for making informed decisions regarding relocation,
investment, or business expansion. This project aims to address several key questions:
• What are the cities and countries with the highest and lowest costs of living?
• What are the major cost components contributing to the overall cost of living in a region?
• How do factors like average salary, housing costs, and transportation expenses correlate with the
cost of living?
• Are there any trends or patterns in the data that can help individuals and organizations make
strategic decisions?


## Dataset Information
The dataset utilized in this project is sourced from Numbeo, a collaborative online database that
provides cost of living information worldwide. It contains 56 columns, including information about cities,
countries, and a wide array of cost-related variables, ranging from grocery prices to real estate costs. The
dataset is designed to offer a comprehensive view of the economic aspects of various locations, making
it a valuable resource for conducting cost of living analyses.

## Tools
Microsoft PowerBI- Data Cleaning and Visualization

## Data Cleaning and Preparation
I performe the following tasks;
Data loading and inspection

Removing columns that were irrelevant to my analysis

Renamimg my columns from numbers to the specific titled provided in the instructions

Replacing nulls values with the arropriate functions

Using the DAX formulas to calculate new columns that were releavant to my analysis 

## Variable Description:
The dataset consists of the following variables:
• City: Name of the city.

• Country: Name of the country.

• ColumnDescription

• city Name of the city

• countryName of the country

• x1 Meal, Inexpensive Restaurant (USD)

• x2 Meal for 2 People, Mid-range Restaurant, Three-course (USD)

• x3 McMeal at McDonalds (or Equivalent Combo Meal) (USD)

• x4 Domestic Beer (0.5 liter draught, in restaurants) (USD)

• x5 Imported Beer (0.33 liter bottle, in restaurants) (USD)

• x6 Cappuccino (regular, in restaurants) (USD)

• x7 Coke/Pepsi (0.33 liter bottle, in restaurants) (USD)

• x8 Water (0.33 liter bottle, in restaurants) (USD)

• x9 Milk (regular), (1 liter) (USD)

• x10 Loaf of Fresh White Bread (500g) (USD)

• x11 Rice (white), (1kg) (USD)

• x12 Eggs (regular) (12) (USD)

• x13 Local Cheese (1kg) (USD)

• x14 Chicken Fillets (1kg) (USD)

• x15 Beef Round (1kg) (or Equivalent Back Leg Red Meat) (USD)

• x16 Apples (1kg) (USD)

• x17 Banana (1kg) (USD)

• x18 Oranges (1kg) (USD)

• x19 Tomato (1kg) (USD)

• x20 Potato (1kg) (USD)

• x21 Onion (1kg) (USD)

• x22 Lettuce (1 head) (USD)

• x23 Water (1.5 liter bottle, at the market) (USD)

• x24 Bottle of Wine (Mid-Range, at the market) (USD)

• x25 Domestic Beer (0.5 liter bottle, at the market) (USD)

• x26 Imported Beer (0.33 liter bottle, at the market) (USD)

• x27 Cigarettes 20 Pack (Marlboro) (USD)

• x28 One-way Ticket (Local Transport) (USD)

• x29 Monthly Pass (Regular Price) (USD)

• x30 Taxi Start (Normal Tariff) (USD)

• x31 Taxi 1km (Normal Tariff) (USD)

• x32 Taxi 1hour Waiting (Normal Tariff) (USD)

• x33 Gasoline (1 liter) (USD)

• x34 Volkswagen Golf 1.4 90 KW Trendline (Or Equivalent New Car) (USD)

• x35 Toyota Corolla Sedan 1.6l 97kW Comfort (Or Equivalent New Car) (USD)

• x36 Basic (Electricity, Heating, Cooling, Water, Garbage) for 85m2 Apartment (USD)

• x37 1 min. of Prepaid Mobile Tariff Local (No Discounts or Plans) (USD)

• x38 Internet (60 Mbps or More, Unlimited Data, Cable/ADSL) (USD)

• x39 Fitness Club, Monthly Fee for 1 Adult (USD)

• x40 Tennis Court Rent (1 Hour on Weekend) (USD)

• x41 Cinema, International Release, 1 Seat (USD)

• x42 Preschool (or Kindergarten), Full Day, Private, Monthly for 1 Child (USD)

• x43 International Primary School, Yearly for 1 Child (USD)

• x44 1 Pair of Jeans (Levis 501 Or Similar) (USD)

• x45 1 Summer Dress in a Chain Store (Zara, H&M, ...) (USD)

• x46 1 Pair of Nike Running Shoes (Mid-Range) (USD)

• x47 1 Pair of Men Leather Business Shoes (USD)

• x48 Apartment (1 bedroom) in City Centre (USD)

• x49 Apartment (1 bedroom) Outside of Centre (USD)

• x50 Apartment (3 bedrooms) in City Centre (USD)

• x51 Apartment (3 bedrooms) Outside of Centre (USD)

• x52 Price per Square Meter to Buy Apartment in City Centre (USD)

• x53 Price per Square Meter to Buy Apartment Outside of Centre (USD)

• x54 Average Monthly Net Salary (After Tax) (USD)

• x55 Mortgage Interest Rate in Percentages (%), Yearly, for 20 Years Fixed-Rate

• data_quality 0 if Numbeo considers that more contributors are needed to increase data
quality, else 1data_quality: A binary variable (0 or 1) indicating data quality, with 0 suggesting
the need for more contributors and 1 indicating satisfactory data quality.

## Analysis
Total countries: Our analysis shows that we have 215 countries in the data

Total cities: From our analysis, we can deduce that our data covers 4898 cities across 215 countries

Cost of Living Index: The Cost of Living Index (COLI) is a valuable tool used to compare the relative price of goods and services across different location.
Cost of living index measures the overall price difference between two locations. It's like a price tag for a basket of essential goods and services in a specific place.
By comparing Cost of living between cities or countries, you can understand how much more (or less) expensive it would be to live in one place compared to another.From our analysis, the United States appears to be the most expensive country based on the Cost of Living Index. However, it is important to consider that this may be a national average and the cost of living can vary significantly between different cities in the US.

Rent index: Rent Index refers to a statistical measure that tracks changes in rental prices over time for a specific region. It's a valuable tool for understanding how affordable or expensive renting is in a particular location. 
Rent Index helps track how quickly or slowly rents are increasing (or decreasing) in a specific area. This can be helpful for both tenants and landlords.
Tenants can use it to gauge how much rent increases they might expect and budget accordingly. Landlords can use it to see how their rental prices compare to the market average and adjust them strategically.
Our analysis shows that Monaco has the highest rent index compared to all the 214 countries with a rent index of 472.91 

Bermuda was the second highest with a rent index of 162.98 

Followed by Singapore with a total of 136.85 

South Sudan follows closely with a total 135.05 and Hongkong was the fifth highest country with a rent index of  115.95

Grocery Price Index:

Transportation Index: Our analysis shows that Djibouti has the highest transportation index with a total of 1.6, followed by Marshall island with a total of 1.05, next on the list is singapore with 0.99 anf United Arab emirates followly closely with 0.86



## Recommendations
If you are considering relocating to a new country, it would be beneficial to research the cost of living in specific cities or regions within that country. This will give you a more accurate idea of the financial implications of your move.

The app can be a useful tool for comparing the cost of living in different countries. However, it is important to remember that other factors, such as quality of life, job opportunities, and personal preferences, should also be considered when making a decision about where to live.

If you're considering relocating, Rent Index data can help you understand the relative cost of renting in different places using the national Indices.Some countries have national rent Indices that track average rental prices across the entire country. 
Also many cities or regions publish their own rent Indices. You can usually find these on the websites of local rental housing associations or government agencies.

Transportation index 

## Limitations
The cost of living indicES displayed may not take into account all of the expenses that you will incur when living in a new country. For example, the cost of healthcare, education, and childcare can vary significantly between countries.
It is important to factor in your own personal spending habits when considering the cost of living in a new location. For example, if you spend a lot of money on dining out or entertainment, you will need to find a city that is affordable for these types of expenses.
