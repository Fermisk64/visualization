    > What software did you use to create your data visualization?
        Microsoft Excel with PivotTable feature

    > Who is your intended audience?
        General audience, as well as, wildlife or student researcher interested in investigating raccoon activity
    
    > What information or message are you trying to convey with your visualization? 
        quantify the raccon encounter/activity during each hour of the day per ward to mpnitor and find the pattern of raccoon activity. Also, the concentration of raccoon population across Toronto
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
            - used color intensity to monitor high vs low activity
            - hours in rows and wards in columns allow locating the exact quantities per hour per ward
            - average values used allows to monitor the pattern over the days the raccoon activity was monitored

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

            - With excel, it depends mostly upon how and what data is selected to be visualized. This makes the reproducibility     more difficult. By using the pivottable, each colun and row corresponds to exact column and row within the dataset. This allows the user understand the data plotted.

    
    > How did you ensure that your data visualization is accessible?  
         Used a single color heatmap allows the colourblind user to distinguish between high and low values based on the intensity of the color, Also, including the values within each cells makes the graph more accessible to any user.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Residents of each ward, wildlife researchers, city planners possibly to adjust waste management policies
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I included:
     - hour: allows understanding the temporal patterns
     - ward_name: for spatial comparisons
     - units_obswrved: to calculate average encounters per hour

    I excluded:
        - date: veraging across dates would result in similar/repititive patterns and cause overcrowded plots
        - other values would only result in noise and were not suitable for what I intended the plots to show

    > What ‘underwater labour’ contributed to your final data visualization product?
        - grouping and averaging the data per hour per ward
        - using single color with varied intensity to distinguish high vs low activity
