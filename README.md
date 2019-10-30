# Data Visualization Project - Franchise Revenue

## Data
This project visualizes [franchise revenue data](https://gist.github.com/vwm/1598b47bed8c5ecdd18dea2fb52680f4/#file-readme-md).  The dataset originates from R for Data Science's Tidy Tuesday weekly event for [July 2, 2019](https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-07-02).

This data shows the revenue of franchises by their media category (e.g., video games, merchandise, etc.), the original media source (e.g., book, film, etc.), the year the franchise was created, the franchise creator, and the current owner.

## Visualizations
...

## Interaction Behavior
The two visualizations feature different interaction styles.  The scatterplot allows the user to dynamically change the Y-axis and color-axis by dropdown menus.  Depending on what is selected, the visualization displays the appropriate data regarding revenue type or legend category.  The stacked bar chart allows the user to highlight segments of the chart by hovering over items in the legend.

## Prototypes
I created an initial prototype which describes revenue by franchise.  It shows the top revenue items and puts franchise revenue into perspective based on media category.

It was immediately interesting to see how merchandise dominates the field. Marvel is the only franchise to appear high in the list from movie revenue, and Shonen Jump represents the highest contribution from the manga category.  This prototype highlighted how useful it would be to include dynamic axis and color selection.

[![image](https://user-images.githubusercontent.com/2779058/65630273-18306980-dfa3-11e9-933f-976104996302.png)](https://beta.vizhub.com/vwm/880af0e6afe24609b87ca5a18faa8a9e)

During the next round of development, I created a prototype that summarizes the total revenue of each franchise by the year it was created.  This prototype revealed the importance of understanding how to handle outliers and raised research questions involving finding more effective ways to present and organize the data under different dimensions.
[![image](https://user-images.githubusercontent.com/2779058/65630754-ff748380-dfa3-11e9-87f7-fbff2ea2b53b.png)](https://beta.vizhub.com/vwm/e99d07afaf75445b8edb3788056b8644)

## Questions & Tasks
These questions served as a guideline and an inspiration for the visualizations' design and interactive elements.  The visualizations are designed to provide the capability to answer these questions.
* How does revenue by revenue category change over time?
* How does the age of a franchise correlate with its total revenue?
* Is there a correlation between the original media type and the relative success of a franchise?
* Which media categories are the most successful, and can any patterns be found to explain why?

## Sketches
Here are some sketches created during project planning.

![image](https://user-images.githubusercontent.com/2779058/65631329-52026f80-dfa5-11e9-8e27-b4a571972155.png)


The right sketch is similar to the first prototype.  This stacked bar concept reveals which factors impact revenue the most and helps determine if any interesting patterns emerge across different dimensions.  An interactive, dynamic selection allows the user to select how to slice the data, making it easier to explore different thoughts and possibilities.

The left sketch is similar to the second prototype.  A spatial view helps show if the original media source and a franchise's total revenue have a correlation.  Ultimately, these two chart types enable a user to evaluate global-level patterns while being able to investigate local-level details.

## Future Work
Link or combine the two visualizations into one visualization with two views.
