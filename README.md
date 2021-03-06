# Module_5
PyBer_Challenge

## Overview
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:

- Deliverable 1: A ride-sharing summary DataFrame by city type
- Deliverable 2: A multiple-line chart of total fares for each city type
- Deliverable 3: A written report for the PyBer analysis (README.md)

## Results: 
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

  **Deliverable 1:** A ride-sharing summary DataFrame by city type <br>
  
Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, get the total number of rides, total number of drivers, and the total fares for each city type. Then, calculate the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns.
![Alt text](https://github.com/f-marquez/Module_5/blob/main/Deliverable1.png)

  **Deliverable 2:** A multiple-line chart of total fares for each city type <br>

Using your Pandas skills and two new functions, pivot() andresample(), create a multiple-line graph that shows the total fares for each week by city type.

 ![Alt text](https://github.com/f-marquez/Module_5/blob/main/Deliverable2.png)
## Summary: 
  **Deliverable 3:** 

A written report for the PyBer analysis (README.md)
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

- **The majority of PyBer's revenue occurs in urban cities** We can that there is a higher usage of PyBer ride-sharing in urban cities therefore we are gonna find more drivers located in urban cities than rural cities.

- **The costs for using PyBer is higher in rural cities than urban cities.**  This could discourage potential riders from rural areas from using PyBer given the high average fare rate. 

- Drivers in rural cities are earning more than drivers in urban cities because there are less drivers available than in the city

