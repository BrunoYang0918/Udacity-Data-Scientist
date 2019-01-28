**1. Libraries Related**

This study is based on Python and those libraries related in this analysis mainly comes from pandas, matplotlib, seaborn, sklearn. To be more specific:

- pandas: data loading and processing
- matplotlib & seaborn: data visualization
- sklearn: data modeling

**2. Motivation**

The purpose of this study is to dig on price related questions using the AirBNB data of Boston from Sep, 2016 to Sep, 2017.
*Areas of Interest*

2.1 What are the busiest times of the year to visit Boston and by how much the prices spikes?
2.2 What are the bed types if listings and their average prices?
2.3 What are the factors that can help to predict house prices?

**3. Files Included**

In this repository, we have provided this jupyter notebook analysis file together with the three csv files with datasets.

**4. Results of Analysis**

*Question One*

Regarding the first question, based on the visualization we could tell that in Sep, 2016, the listing availability is quite low. Only around 30% of the listings are available and the price on average is $50 higher than the rest of the time of that year.
Question-1
In the meantime, we could also notice from the below graph that this phenomenon does not apprear the next year. We could infer that there might be some special events (outside reason) or promotion (internal reasion), leading to the increasement of prices and reduction of availability.

*Question Two*

By looking at the graph attached, we could tell that listings on AirBNB together have 5 different bed types and among them real bed is the most expensive. In general, the price of a real bed listing is almost 2 times of others.

*Question Three*

The study to predict a listing price is mainly based on those parameters from the listings file. There are various factors considered in the model, such as number of bedrooms, beds, accommodates; type of rooms, bed etc. We have successfuly processed the data and build up a random forest model. H