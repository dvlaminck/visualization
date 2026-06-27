# Visualization 2
## Bike_Theft_Counts_Toronto_Vis2.png
### Source data: https://open.toronto.ca/dataset/bicycle-thefts/, used version from April 23, 2026. Contains information on bicycle thefts in Toronto, including location, date, and type of theft.
    
    > What software did you use to create your data visualization?

    I used Python to create the visualization, specifically with the matplotlib library since it can be dome programatically and is reproducible.

    > Who is your intended audience? 

    The intended audience is similar to the other visualization. Toronto residents who cycle who are considering where to store their bikes. As well, this plot is extremely useful for the Toronto Police Department trying to control bike thefts within the city.
    
    > What information or message are you trying to convey with your visualization? 

    The main message from this visualizationis that bicycle theft in Toronto is concentrated in a small number of premises. Namely, apartments and outside account for over half of the total thefts in Toronto. The ranking is clear from the plot with the most common location for theft at the top and longest bar, with each bar decreasing as the eye is drawn down.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    I considered many aspects we discussed in class such as Gestalt principles, cognitive load and Kennedy et al. guidelines. It follows all the Kennedy et al principles being: 2-D image, clean layout, use of solely geometric shapes and lines, and inclusion of the data source. I have also tried to reduce the cognitive load that it takes to interpret my graph as much as possible. For example, it is a familiar chart type and has absolute values to interpret which are written and can be visually determined easily due to gridlines. One key thing about this plot is that it has a very clear contrast which is made clear with the Gestalt principles. The continuity in the length of bars shows a clear ranking and draws your eye to the most important elements first.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    To ensure my visualization is reproducible, I created it in Python. The script can be run programatically and anyone can reference my code to see how it was created. As well, my code is clearly commented so that it can be easily interpretable to anyone who looks at it. In comparison to other softwares, there is a clear record of how my visualization was produced. As well, within my plot, I made sure to include my source data and version used. This way, anybody who is trying to reproduce my plot knows exactly where my data was gathered from, not to mention I used open-source data.
    
    > How did you ensure that your data visualization is accessible?  

    I have made this visualization accessible by clearly labelling all axes and having a descriptive title for my plot. All font sizes were kept to 12pt or higher to make them easily readable for the viewer. Furthermore, using a familiar chart type (line) allows the reader to use a decreased cognitive load and requires less interepretation. The bars use blue which is typically colour-blind friendly, and the same colour for all the bars prevents any confusion.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    This visualization impacts people in apartment buildings since they are the leading category for bike theft. It is unclear whether this clear rise in bike thefts is due to the 'unsafe' nature of an apartment building or they are just more dense with people. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    This was a pretty straightforward visualization that really focused on one element so all other elements of the dataset were excluded.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Again, the distinction here between occurence date and reporting date is important. Additionally, I knew percentages would be helpful here for interpretation so that was something I had to calculate from my data.