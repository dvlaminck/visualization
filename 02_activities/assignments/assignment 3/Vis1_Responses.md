# Visualization 1
## Bike_Theft_Counts_Toronto_Vis1.png
### Source data: https://open.toronto.ca/dataset/bicycle-thefts/, used version from April 23, 2026. Contains information on bicycle thefts in Toronto, including location, date, and type of theft.
    
    > What software did you use to create your data visualization?

    I used Python to create the visualization, specifically with the matplotlib library since it can be dome programatically and is reproducible.

    > Who is your intended audience? 

    The intended audience is Toronto residents who cycle, so they can be aware of when to be on high alert for thefts. Similarly, this plot is extremely useful for the Toronto Police Department/ City Planners who will track theft patterns. Because of the simple chart style and accesibility of this visualization, this plot is more broadly meant to be interpreted, and can be, interpreted by anyone who has an interest in this information.
    
    > What information or message are you trying to convey with your visualization? 

    The clear message from this visualization is that there is a strong seasonal pattern in bike thefts in Toronto; There is a steady rise starting in the spring, which peaks around June/July and then declines again. Logically this makes sense due to the weather changes in Toronto during these months -- Many more bikers are riding in the summer months. This plot also highlights a decrease in the total number of thefts in recent years across Toronto. In fact, the past year of 2025 is clearly lower than the other years for virtually every month. Therefore, this plot also highlights that bike thefts are trending downwards over time since 2018.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    I considered many aspects we discussed in class such as Gestalt principles, cognitive load and Kennedy et al. guidelines. It follows all the Kennedy et al principles being: 2-D image, clean layout, use of solely geometric shapes and lines, and inclusion of the data source. I have also tried to reduce the cognitive load that it takes to interpret my graph as much as possible. For example, it is a familiar chart type and absolute values can be visually determined easily due to gridlines. The Gestalt principles are included in my plot elements with connection and continuity within a given year. As well, years (similarity) are grouped by colour.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    To ensure my visualization is reproducible, I created it in Python. The script can be run programatically and anyone can reference my code to see how it was created. As well, my code is clearly commented so that it can be easily interpretable to anyone who looks at it. In comparison to other softwares, there is a clear record of how my visualization was produced. As well, within my plot, I made sure to include my source data and version used. This way, anybody who is trying to reproduce my plot knows exactly where my data was gathered from, not to mention I used open-source data.
    
    > How did you ensure that your data visualization is accessible?  

    The data is accessible since it uses the viridis package which is intended to be accesible to individuals who are colour blind. In addition, I also have very clearly labelled all axes and given a descriptive title for my plot. All font sizes were kept to 12pt or higher to make them easily readable for the viewer. Furthermore, using a familiar chart type (line) allows the reader to use a decreased cognitive load and requires less interepretation.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    The people most impacted by my visualization are the cyclists living within Toronto. This visualization could help to inform them when to leave a bike outdoors. Toronto Police Services and city planners may also use this chart to allocate their resources. For example, in the summer months, they may choose to have more officers patrolling for bike thefts.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    This chart focuses on timing of bike thefts. Therefore, anything unrelated to this (involved in a different question) was excluded. For example, location of the theft, status of the theft, etc. were removed for this reason. I also excluded the exact dates of the theft (opting only to use the month/year) to avoid creating too complex of a visualizationa and making it too cluttered.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    One tricky thing about this dataset is that when the bike theft happens, it is not necessarily reported right away. It was important for me to make the distinction between occurance date vs reporting date. As well, I had to restructure my data to group by both the month and the year.