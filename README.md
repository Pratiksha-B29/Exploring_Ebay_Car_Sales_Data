# Exploring_Ebay_Car_Sales_Data

Project Overview
The aim of this project is to clean and analyze a dataset of used car listings from eBay Kleinanzeigen, the German eBay website's classifieds section. This dataset was originally scraped and uploaded to Kaggle and has been further prepared by Dataquest, including simulated messier data to challenge our cleaning efforts.

We will be working with a sample of 50,000 data points that represent various used car listings. The analysis will primarily focus on cleaning the data and drawing insights on car prices, mileage, and other factors. 

The data dictionary provided with data is as follows:

- dateCrawled - When this ad was first crawled. All field-values are taken from this date.
- name - Name of the car.
- seller - Whether the seller is private or a dealer.
- offerType - The type of listing
- price - The price on the ad to sell the car.
- abtest - Whether the listing is included in an A/B test.
- vehicleType - The vehicle Type.
- yearOfRegistration - The year in which which year the car was first registered.
- gearbox - The transmission type.
- powerPS - The power of the car in PS.
- model - The car model name.
- kilometer - How many kilometers the car has driven.
- monthOfRegistration - The month in which which year the car was first registered.
- fuelType - What type of fuel the car uses.
- brand - The brand of the car.
- notRepairedDamage - If the car has a damage which is not yet repaired.
- dateCreated - The date on which the eBay listing was created.
- nrOfPictures - The number of pictures in the ad.
- postalCode - The postal code for the location of the vehicle.
- lastSeenOnline - When the crawler saw this ad last online.

The steps below outline the process followed to achieve these goals.

## Dataset
- Source: eBay Kleinanzeigen used car listings dataset (originally scraped and uploaded to Kaggle)
- Sample size: 50,000 listings

## Steps Involved 

**1. Cleaning Columns:**

- Renamed columns for better readability and usability.
- Dropped unnecessary or duplicate columns that don’t contribute to analysis.

**2. Initial Data Exploration & Cleaning:**

- Explored the dataset to understand the distribution of values, missing data, and anomalies.
- Handled missing and incorrect data, addressing extreme outliers in features like price and mileage.

**3. Exploring Odometer and Price columns**

- Cleaned and analyzed the Odometer and Price columns.
- Identified outliers and dropped unrealistic values (e.g., extremely high or low prices).

**4. Exploring Date column**

- Parsed and analyzed date columns (e.g., listing date) to ensure valid formats.
- Investigated any inconsistencies or missing dates.

**5. Dealing with Incorrect Registration Year Data:**

- Handled incorrect registration_year data, identifying and addressing invalid entries.
- Dropped or corrected registration years outside a realistic range for car listings.

 **6. Exploring Price by Brand:**

- Analyzed price distribution by car brands to identify trends and patterns.
- Visualized which car brands hold higher resale values and potential outliers in pricing.

**7. Exploring Mileage**

- Investigated how car mileage varies across different brands.
- Explored correlations between price and mileage to understand factors impacting used car prices.

## Conclusion 

This project involved cleaning and analyzing a real-world dataset of used cars from eBay Kleinanzeigen. Through this analysis, we gained insights into trends in car pricing, mileage, and registration year data. We also identified outliers and cleaned inconsistencies in the dataset, improving its quality for analysis. By the end of this project, we were able to spot trends across different car brands and mileage, which can inform future buyers or sellers about car pricing in the used car market.

## Tools & Libraries Used

- Python (Pandas, NumPy)
- Jupyter Notebook



  
