# PyBer Analysis
**Data Analyst at PyBer**
Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

## OVERVIEW
PyBer CEO has given you and your manager a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. 

> Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

1. ***Deliverable 1***: A ride-sharing summary DataFrame by city type
2. ***Deliverable 2***: A multiple-line chart of total fares for each city type
3. ***Deliverable 3***: A written report for the PyBer analysis [`README.md`](https://github.com/DataJew/PyBer_Analysis). 

## Deliverable 1:  A Ride-Sharing Summary DataFrame by City Type
### Deliverable Requirements:

1. The total number of rides for each city type is retrieved. 
2. The total number of drivers for each city type is retrieved.
3. The sum of the fares for each city type is retrieved.
4. The average fare per ride for each city type is calculated.  
5. The average fare per driver for each city type is calculated. 
6. A PyBer summary DataFrame is created.
7. The PyBer summary DataFrame is formatted as shown in the example.

[`Deleveriable 1 Results`](https://github.com/DataJew/PyBer_Analysis/blob/master/PyBer_Challenge.ipynb)

### Deliverable 2: A multiple-line chart of total fares for each city type
### Deliverable Requirements:

1. A DataFrame was created using the `groupby()` function on the "type" and "date" columns, and the `sum()` method is applied on the "fare" column to show the total fare amount for each date and time.
2. A DataFrame was created using the `pivot()` function where the index is the "date," the columns are the city "type," and the values are the "fare."
3. A DataFrame was created using the `loc` method on the date range: 2019-01-01 through 2019-04-28.
4. A DataFrame was created using the `resample()` function in weekly bins and shows the sum of the fares for each week.
5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 

[`Deleveriable 2 Results`](https://github.com/DataJew/PyBer_Analysis/blob/master/PyBer_Challenge.ipynb) 

## Deliverable 3: A written report for the PyBer Analysis
### The analysis should contain the following:

1. **Overview of the analysis** 
* Explain the purpose of the new analysis:

    > The purpose of this written report for Data Analyst at PyBer is to create a complete summary of the Ride-Sharing data by city type. Including a quick summary of line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib libraries. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics. Our Final Analysis include multiple-line graphs of total weekly fares for each city type.


2. **Results** 
* Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types:

    > * The Suburban fares started around $1,000, and the analysis was not profitable, fare dropped in March and in mid-April.  
    > * The Rural fares started at around $200, the analysis shows fares increase and dropped till the end of April.  
    > * The Urban fares start with an average of $1,800 with a consistent increase around 2,300. 
    
     > The PyBer summary DataFrame, 
     ![name-of-you-image](https://github.com/DataJew/PyBer_Analysis/blob/master/analysis/images/PyBerSummarydf.png) 
   

     > A multiple-line chart of total fares for each city type,
     ![name-of-you-image](https://github.com/DataJew/PyBer_Analysis/blob/master/analysis/images/PyBer_fare_summary.png) 
    

     > PyBer Ride-Sharing Data (2019),
     ![name-of-you-image](https://github.com/DataJew/PyBer_Analysis/blob/master/analysis/images/PyBerRide-SharingData(2019).png)  
      

3. **Summary** 
* Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types:

    > **1)** From our analysis, we can predict that there are good opportunities to expand the business in rural and suburban cities, including hiring drivers to operate and explode business in rural and suburban cities.

     > % of Total Drivers by City Type,
     ![name-of-you-image](https://github.com/DataJew/PyBer_Analysis/blob/master/analysis/images/TotalDriversbyCityTypePieChart.png) 
  
    
    > **2)** The Urban cities fare is the highest and consistent, giving us great and new business opportunities to expand rides.  

     > % of Total Fares by City Type, 
     ![name-of-you-image](https://github.com/DataJew/PyBer_Analysis/blob/master/analysis/images/PercentageofFaresbyCityType.png) 

    
    > **3)** The Rural cities fare is the lowest of the other two city types (Urban and Suburban cities), in addition, fares never intersect.  Knowing that all fares never intersect, we can expand fares and increase business financial income to the company without affecting our rate.

     > Total Fare by City Type,
     ![name-of-you-image](https://github.com/DataJew/PyBer_Analysis/blob/master/analysis/images/PyBer_fare_summary.png) 
   
