# PyBer Analysis

## Project Overview
The purpose of the PyBer Analysis project was to use Python and Pandas to perform data analyis to understand how ride share data differed between urban, rural, and suburban city types.  Pyber will then use the results to make strateic business decisions to grow their company.

## Results
We started off by reading city and driver csv files into pandas dataframes.  We then merged the two dataframes to make a single dataframe.  We used the groupby function to summarize the data based on city type.  We also used the pivot function so that we could transform the data where the date is the index.  We then plotted this data

The data from the ride summary by city type dataframe confirms what one would expect the data to show.  There are more rides in urban areas than in suburban and rural areas.  Additionally, there are more drivers in urban areas than in suburban and rural areas to support the higher number of rides.  This could be that more people that live in suburban and rural areas are more likely to own cars and therefore do not need ride share services as often.  Also, you can see that on average, rides in rural areas are more expensive than rides in urban and suburban areas and that the drivers also make more per ride.  This is most likely due to the longer distances and travel times that are expected in rural areas.  The majority of PyBer's revenue is generated from rides in urban areas due to the volume of rides in that area.  The trends for Weekly Fares by City Type are pretty similar with the exception of suburban fares in April.  We see that suburban fares increase while fares in urban and rural areas decrease.  Additional data would be needed in order to udnerstand why this deviation occurs.


### Summary DataFrame by City Type
![PyBer Ride Summary DataFrame](https://github.com/cadejackson/PyBer_Analysis/blob/main/Resources/Ride%20Summary.png)

### Pivot Table by Week Filtered by Date Range
![PyBer Pivot Table](https://github.com/cadejackson/PyBer_Analysis/blob/main/Resources/PyBer%20Pivot.png)

### PyBer Resample by Week Line Chart
![PyBer Line Chart](https://github.com/cadejackson/PyBer_Analysis/blob/main/Resources/Weekly%20Fares%20by%20City%20Type.png)


## Business Recommendations

Although rural areas generate more money per ride, over 60% of revenue is generated in urban cities and over 90% of revenue is generated in urban and suburban cities.  This tells us that PyBer should continue to focus on urban and suburban cities to continue growing.  PyBer could consider incentavizing drivers to be in suburban areas in April due to the increase in fares that we see in that month compared to other citiy types.  PyBer could consider offering monthly packages to urban drivers where activity is higher.  This could bring in more revenue and increase the liklihood that they use PyBer over other ride share services.

