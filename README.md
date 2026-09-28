# Project-2-Electric-Vehicles

## Problem Statement:
- Electric Vehicles companies struggle to compete with TESLA in terms of number of vehicles based on Washington State data base; with TESLA holding %45 and the closest competitor has %8

## Executive Summary:
- This project studies the State of Washington data base of electric vehicles from the oldest model of 1997 to the newest ones in 2024

- Limitations:
  - 98.12% of the Data Frame is missing the "Base MSRP"
  - 51.69% of the Data Frame is missing the "Electric Range"

The "Yaser_Abdulla_Project_2.ipynb" file shows handling the data and creating new variable called `is_TESLA` to differentiate between TESLA vehicles and others, then it visualize the growth of the electric vehicles market and compares the growth of TESLA and others. The next step in the file is comparing the CAFV percentage between TESLA and competition. Finally the notebook compare between the battery types and exclude the unwanted type for visualizing and comparing the ranges of the electric vehicles.

## Conclusion:
- The Data Frame misses the Base MSRP and that limited us from taking the price into consideration for our analysis
- We see that the Electric Range has a huge affect on the number of vehicles so increasing the range for the future models will help in selling more
- We see that All the TESLA vehicles are CAFV Eligible and that could be a factor for customers to buy them to get tax exemption, but the CAFV incentive has expired on (July 31, 2025) and probably would not be a factor in the near future.

## File Directory:
- Yaser_Abdulla_Project_2.ipynb
- Electric_Vehicle_Population_Data.csv
- Electric_Vehicles.ppt

## Areas for Further Research:
- Having the full or most of the data in the "Base MSRP" would help to study the affect of the prices of each model.
- Studying the data after the CAFV incentive expiration would help study the affect of the incentive on the previous data

## Sources:
- https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population/data/code
