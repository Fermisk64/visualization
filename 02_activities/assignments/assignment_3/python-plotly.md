    > What software did you use to create your data visualization?
        Python inside jupyter notebook

    > Who is your intended audience?
        General audience, as well as, wildlife or student researcher interested in investigating raccoon activity
    
    > What information or message are you trying to convey with your visualization? 
        Average raccoon activity based on the hour of the day per ward. This allows monitoring how this activity differs among different Toronto wards, and in which wards the raccoons are mostly concentrated based on their activity. Overall, this plot allows detecting the pattern of raccon encounter/activity during 24 hour period per ward. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
            - Since I was monitoring the activity per hour, I used a polar plot to better visualize based on the hour of the day
            - The clock orientation needed to mimic the real clock
            - Used color encoding to distinguish between wards
            - The interactive hover feature allows more accurate values for files included
   

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
            - It is code based which means anyone with the access to the code can reproduce it.
            - adding comments for each function or transformation helps the person understand the purpose of each transformation


    
    > How did you ensure that your data visualization is accessible?  
    Python: considering the number of wards including, avoiding colors that overlap for colorblindness was somehow difficult. To make the plot more accessible, the hover feature allows the audience to distinguish among wards
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Residents of each ward, wildlife researchers, city planners possibly to adjust waste management policies
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I included:
     - hour: allows understanding the temporal patterns
     - ward_name: for spatial comparisons
     - units_observed: to calculate average encounters per hour

    I excluded:
        - date: veraging across dates would result in similar/repititive patterns and cause overcrowded plots
        - other values would only result in noise and were not suitable for what I intended the plots to show

    > What ‘underwater labour’ contributed to your final data visualization product?
        - grouping and averaging the data
        - converting the hours into angles of a clock
        - choosing the color palette that is more colour-blindness friendly and also line thicknesses to avoid clutter/over crowded plots
        - adjusting the plot rotation accoring to clock orientation
        - ensuring reproducibility of plots
        - adding the interactive hover feature