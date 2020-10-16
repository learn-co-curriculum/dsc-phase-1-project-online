## Creating Successful Original Content

### Data

1. [The Numbers](https://www.the-numbers.com/home-market/netflix-daily-chart/2020/06/01) | Netflix Daily Top 10 
2. [Kaggle - Netflix DB](https://www.kaggle.com/shivamb/netflix-shows) | Available shows and movies on Netflix, supplemental DB from Kaggle
3. [Emmy's Nominations](https://www.emmys.com/awards/nominees-winners) | Emmy Award Nominations and Winners 
4. [TV Series](https://tvseriesfinale.com/television-ratings/) | Ratings and Viewership for most popular TV shows by network

### Analysis Methods

Descriptive analytics are used throughout this project to better understand the streaming industry, specifically regarding TV series. The purpose of this analysis is to better understand the factors that contribute to creating successful content. Some of the methods used in this project are as follows:

1. Web scraping,
2. Creating, cleaning, and joining data frames,
3. Categorical & quantitative analytical methods, 
4. Visualizations using Seaborn and Matplotlib.

### First Thoughts and Hypothesis

In recent years, the popularity of streaming services has been revolutionized by companies such as YouTube, Netflix, HBO and many others. Consumer's habits have changed in response to this. Why travel to a movie theater to pay a premium on tickets and concessions when you can watch whatever you'd like from the comfort of your own home?

Because of this trend, we decided to look at success rates of movies and TV shows in the past years to better advise Microsoft in creating successful orginal content. To determine success, it's necessary to look at key areas of the entertainment industry - viewership, ratings, and award nominations. Beacuse higher viewership corresponds to a larger number of paying subscribers, we believe viewership is the key to success for any original content. It's also been shown that advertising companies pay a premium for shows with higher viewership.
After researching these three areas, we determined the best strategy for creating original content is by creating a TV series.

![Advertising](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/Advertising.png)

### Question 1: What type of content is most successful today? 
#### What type of content is being created today? 

The first question anyone looking to create original content asks is, "What should we create?" By looking at what is currently being created, and the trend over the last several years is a good place to start. Considering the current socialeconomic situation, it can be expected that a majority of people will be engaging with original content from their homes. Because of this, we decided to look at types of content being published on streaming services. 

Below, the trends for both TV shows and movies are obvious. While movie releases have begun to sharply decline in the past three years, TV shows are trending upward and have surpassed movie releases in the recent years.   

![TypeTrend](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/TypeTrend.png) 

#### TV Shows are being released at a higher rate than movies, but are they also more popular? 

Although TV Shows are being produced at a higher rate than movies, that doesn't necessarily mean they're more popular with viewers. To determine what viewers are consuming, we turned to the Netflix Daily Top 10. Earlier this year Netflix released a universal Daily Top 10, which shows the viewer the ten most popular shows and movies for that day. This data, as we can clearly see below, proved that TV Shows are more popular than movies as TV shows appeared in the Daily Top 10 more frequently than movies. TV shows also received higher viewership scores than movies. 

![Top10Types](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/Top10Types.png)

### Question 2: Which network or streaming service would best support our series?   

Leveraging an existing platform, whether it's a network or streaming service, that already has proven success will allow Microsoft to focus on creating innovative content. Choosing the correct platform for a new TV series is crucial to the show's success. 

#### Which network | streaming service has received the most award nominations in the last four years? 

Award shows are a great way to evaluate the success of a TV show and their corresponding platform. The Emmy's are well-known and much talked about, making this the perfect award show to help us determine which network or streaming service would be the best platform to host a new TV show.

After pulling shows and actors nominated for major award from the Emmy's site, it was obvious that several networks have been more successful than others over the last few years. As you can see in the chart below, HBO, Netflix and Prime Video have out-performed all other networks, with HBO clearly in the lead. 

![TotalNominationsAllNetworks](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/TotalNominationsAllNetworks.png) 


#### Which network | streaming service has had the most shows nominated? 

Looking at the top three winningest networks, we can see that eight HBO shows, eleven Netflix shows, and two Prime Video shows have been nominated for an Emmyin over the last four years. One could argue that Netflix has been the most successful considering they have a higher number of shows nominated, however you can see below that the eight HBO shows were nominated for a larger number of awards than the Netflix shows. This means that the eight HBO shows are more successful than the eleven Netflix shows considering more awards were won per show. 

![ShowNominations](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/ShowNominations.png)

#### We believe that HBO is the best network to host Microsoft's new original TV series.

Above, we presented two arguments that present HBO as the clear choice: 
1. From 2017-2020, HBO has collected far more nominations than the competing networks 
2. While Netflix has had more shows nominated for awards in the last two years, HBO is close behind and shows a higher success rate per show than Netflix 

Finally, HBO also proves to draw a larger viewership than other popular networks further solidifying the recommendation to choose HBO to host a new TV show. 

![NetworkViews](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/NetworkViews.png)

### Question 3: What genre of show will be profitable? 
#### Insight

In todays subscription structured business models, two of the most important variables that determines success are viewership and ratings. 

#### Which genres generate the most views? 

With this in mind, I found viewership numbers from four popular networks. From this analysis there were five genres with the most views for TV series. They are as follows:

1. Drama
2. Comedy
3. Crime
4. Action
5. Fantasy

![TopGenres](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/TopGenres.png) 


#### Which genres are most highly rated? 

After seeing that the genres above were clearly viewed at a much higher rate than others, I wanted to know which of those genres had the highest rating. Expecting Comedy or Drama to have the highest ratings, it was surprising to find that Fantasy actually had the most top ratings. 

![HeatmapGenres](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/HeatmapGenres.png) 


#### Which genre should Microsoft choose for their new TV series? 

It's clear that Drama is the most viewed genre for all four networks. Comedy, Action and Crime genres all trail close behind and could also be worth investment. 

In order to break into this industry, I would recommend developing a tv series with the genre Drama being the foundation, considering Drama drives the highest number of viewers for all four networks as seen below. Because Fantasy and Crime shows appear to pull highest ratings, adding a Fantasy or Crime element could be beneficial. 

![GenresByNetwork](https://github.com/drrausch/dsc-phase-1-project-online/blob/master/Images/GenresByNetwork.png) 


### Conclusion

To create successful original content, we recommend the following: 

1. Create a TV show as opposed to a movie 
2. Work with the most successful platform, HBO, to host the new TV show
3. Create a show with a main genre of Drama while possibly adding elements of either Fantasy or Crime to drive ratings 
