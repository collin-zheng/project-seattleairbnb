# A look at Seattle's AirBnb scene

### Table of Contents

1. [Motivation](#motivation)
2. [Data and Libraries](#requirements)
3. [Results](#results)
4. [Blog](#blog)

## Motivation <a name="libraries"></a>

As a keen traveller and investor, I'm interested in the AirBnb market for cities around the world. Here, we take a look at the Seattle market. For this project, I looked at four questions:

1. How do the Airbnb rental prices vary seasonally?
2. What types of properties are the most popular?
3. How does cancellation policy affect a rental?
4. How does host response times affect a rental?

## Data & Libraries <a name="requirements"></a>

The analysis requires Jupyter Lab (Anaconda 1.0.2, Python 3.6). Important libraries include: NumPy, Pandas, Matplotlib, Seaborn and Sklearn.

The analysis can be found in a Jupyter notebook: 
- Project_SeattleAirbnb.ipynb.

Three tables are used for the analysis: 
- calendar.csv: table of 1.4 million records on every listing for each day for roughly a year in Seattle.
- listings.csv: table of 3,800 listings available to rent during that time.
- review.csv: table of 85,000 user reviews. This data was not directly used for this analysis, but may be useful for future extensions.

## Results <a name="results"></a>

In short, I found that the median prices of rentals were the highest in summer; that apartments and houses were the most common rentals, and also the most popular; that the most popular rentals had the most generous cancellation policies; and that the most popular rentals had the quickest enquiry response time by their hosts.


## Blog <a name="blog"></a>
Here's my [blog](https://medium.com/@col_jung/travelling-or-investing-seattles-airbnb-scene-a4d8e613a1ca "blog") post about this project.