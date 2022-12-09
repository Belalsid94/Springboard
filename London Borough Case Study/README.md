London Housing Case Study - Findings


1. What did you find? Which borough is the most expensive? Any other interesting trends?
        
Over the last 2 decades, out of all 32 boroughs in Greater London, Hackney has seen the greatest increase in average housing prices. In other words, Hackney has been the most desirable borough to live in for the people of the Greater London area. Hackney is followed by Waltham Forest, Southwark, Lewisham and Westminster boroughs. 


An interesting observation was the dip in average prices when the pandemic hit, which is consistent across all boroughs.

2. How did you arrive at your conclusion?


The dataset provided by the London Datastore includes average monthly housing prices across all boroughs. After cleaning and massaging the data, the ratio of average housing prices in 2018 over average prices in 1998 (20 year gap) was calculated and plotted against the top 15 boroughs displaying the greatest increase. It is evident from the visualization that Hackney has seen the greatest increase in average housing prices.
  

3. What were the main challenges you encountered? How did you overcome them? What could you not overcome?


* Monthly data was providing too many data points to get a good visualization. To tackle this, the data was grouped by years and not months.
* The dataset included a lot of data for areas in and around London which are not included in the list of London boroughs. External source (Google) was used to confirm the list of 32 boroughs. 
* The dataset included 2 types of null values, datetime and float types, which created confusion in renaming some values. pd.NaT was used instead of np.NaN to rename datetime null values.


4. Is there anything you’d like to investigate deeper?


Instead of taking ratios, other methods such as simply taking the difference between the average prices over 2 decades could be used to see if the trends are consistent.