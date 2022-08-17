# Used Car Data Exploration
## by David Kayode Oluwadare


## Dataset

There is an automobile company in the India which aspires to enter the used-car market by setting up their company locally to give competition to their counterparts. Based on various market surveys, the consulting firm has gathered a large dataset of different types of used   cars across the market.
> Source : https://www.kaggle.com/datasets/shubham1kumar/usedcar-data?select=UserCarData.csv

#### Data Dictionary:

* Sales_ID (Sales ID)
* name (Name of the used car)
* year (Year of the car purchase)
* selling_price (Current selling price for used car)
* km_driven (Total km driven)
* Region (Region where it is used)
* State or Province (State or Province where it is used)
* City (City where it is used)
* fuel (Fuel type)
* seller_type (Who is selling the car)
* transmission (Transmission type of the car)
* owner (Owner type)
* mileage (Mileage of the car)
* engine (engine power)
* max_power (max power)
* seats (Number of seats)
* sold (used car sold or not)


## Summary of Findings


This is a large dataset of different types of used cars, trying to break through the market. There are thirty-one brands of cars which range accross Maruti, Hyundai, Tata, Mercedes, BMW, Toyota, just to mention but a few. Mileages and kilometer driven are great factors to be put into consideration in sales of used cars. The Higher the mileage, the faster the car, the higher the kilometer driven, the weaker the engine. Almost all of the cars range from 0-500,000 in km except for some Maurati and Toyota greater than 500,000km.

* The Maruti cars have the highest **mileage**, they are above 30 km/hr

* Maruti, Hyundai, Mahindra, Tata are clearly the cars with the most **individual Seller_Type**.

* Maruti and Hyundai, have petrol as their highest **fuel** usage, while; Toyota, Ford, Mahindra, Tata, are the cars with the highest Diesel usage 

* Maruti, Hyundai, Mahindra, Tata are the cars with the highest Manual **transmission**, and cars like Mercedes, BMW, Lexus, Jaguar, Volvo are the cars with the highest Automatic Transmission.

* Most of the used cars have not been **sold**. Marauti have the highest number of unsold cars followed by Hyundai, Mahindra, Tata...


Among many features it can be said that Year, Name, Region & State are categories which affect buying and selling of car. Fuel feature does not affect buying and selling of car. The greater the year, the costler cars became. At around 2010, cars were less than 3million INR, and later increased gradually above 6million INR from 2017-2019


* It is assumed that because most of the cars are purchased between 2017-2019 hence, less number of cars are being sold.

* Fewer cars was sold in the year 1995 and below at a price lesser than 1m INR

* Car prices increase with the ascending year.


## Key Insights for Presentation

> Understanding in details the Selling price of cars by Year, In what year did Used cars got costler?

> Understanding in details the State/Province of cars by Mileage and Km Driven, What are the Provinces where the cars were used the most

> Accertain if cars were sold and perhaps the seller type, Which cars were sold and which are not sold yet?