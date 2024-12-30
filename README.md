# Car-Sales-Analysis-Dashboard

This **Car Sales Analysis Dashboard** is designed to help users explore car sales data through filters and interactive visualizations. It summarizes key metrics, such as total sales value (3.51bn), number of sales (2059), and average sale price (1.70M). These figures are presented alongside charts and slicers that make the data easy to analyze.  

The dashboard includes several slicers for filtering data:  
- **Year**: Filter by a specific year or a range of years (e.g., 2008–2022).  
- **Make & Model**: View data for specific car brands or models.  
- **Owner Type**: Analyze sales based on ownership history, like first-owner or second-owner cars.  
- **Seating Capacity**: Focus on vehicles with a specific number of seats.  
- **Kilometer Run**: Filter cars based on the distance they have been driven.  
- **Engine Size**: Narrow down cars by engine capacity, from smaller engines to larger ones.  

These slicers allow users to customize their view. For example, selecting "Honda" in the Make & Model slicer will update all visuals to show data for Honda cars, which can be further refined with other slicers like year or drivetrain type.  

The dashboard also supports **interactive chart filtering**. Clicking on a part of any chart updates the rest of the visuals to reflect that selection. For instance, selecting "Automatic" in the transmission pie chart will filter all data to show only automatic cars while respecting other slicers.   

The visualizations include bar charts for top-selling models, pie charts for drivetrain and fuel types, a time-series chart showing total sales by year, and a map of sales locations.

Here's what the dashboard looks like:

![alt text](https://github.com/itsmabdulrehman/Car-Sales-Analysis-Dashboard/blob/main/snapshot.png?raw=true)

## Dataset

**Dataset Overview**:  
This dataset, sourced from Kaggle, contains details of 2000 used vehicles from the Indian automotive market, including both numerical and categorical variables suitable for linear regression analysis of resale prices.

**Size and Structure**:  
- **Total Entries**: 20 rows  
- **Attributes**: 20 columns, both numerical and categorical  

**Key Attributes**:  
- **Make and Model**: Categorical (vehicle manufacturer and model)  
- **Price**: Numerical (resale price, dependent variable)  
- **Year and Kilometers**: Numerical (manufacturing year and mileage)  
- **Fuel Type, Transmission, Drivetrain**: Categorical (fuel type, transmission system, drivetrain type)  
- **Dimensions and Specifications**: Numerical (engine capacity, power, torque, vehicle dimensions)  
- **Ownership and Seller Type**: Categorical (ownership history, seller type)  
- **Location and Color**: Categorical (location, color)

**Data Types**:  
- **Numerical**: Price, mileage, engine capacity, power, dimensions  
- **Categorical**: Make, model, location, fuel type, transmission  

**Source**:  
The dataset is publicly available on Kaggle (https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho/data).
