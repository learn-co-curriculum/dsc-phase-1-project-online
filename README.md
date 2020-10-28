# Microsoft Movie Analysis


### Business Problem

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.
Your team is charged with exploring what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `zippedData` are movie datasets from:

* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org


### My Questions

1. Which production studio has the highest average performance?

2. How does the production budget correlate with the world wide gross and the domestic gross?

### My Process

Fist we took the data loaded it into a jupyter notebook with pandas and turned therm into datatframes. Then we cleanned the data up to we could use it in our analysis. Then we used seaborn to set up the visuliztions comparing how buget corilates with gross imcome of films. We decided to use a scatter plot with a regression line on it to show what the trend was. Then for the production studios highest average we took the top ten production studios based off of there total income and put the average gross income for each of the movies they made and used a bar graph to show this. 

## Results

The red regression line shows that there is a clear positive correlation between a larger budget and more gross income for domestic and worldwide gross.


These are the top ten movie studios based on there total gross income. The graph shows which studios have the highest average gross income per movie. Teaming up with either Dreamworks (P/DW) as the 1st option  or Buena Vistas (BV) as the 2nd option will give you the best probability for a higher grossing movie.
