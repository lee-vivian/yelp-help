# yelp-help

An analysis of Yelp restaurant data. Uses 5-fold cross validation to identify the most significant features for a given niche and construct a final polr model to predict a restaurant's Yelp rating given certain feature values.

Authors: Kristy Chen and Vivian Lee

Many people use Yelp to find new restaurants and try the latest food trends. In fact, Yelp’s mission statement
is “to connect people with great local businesses.” While the search service has certainly succeeded in allowing
users to find highly rated businesses tailored to their needs, it often hurts businesses that are assigned lower
ratings and consequently do not appear in the first few returned search result pages. These businesses are
often written off as bad options by potential customers based on their poor ratings or ignored by users who
refuse to give them a chance.

Our goal was to use data collected from Yelp to help restaurants determine actionable changes they can
implement to improve their Yelp ratings, which would have a direct influence on their sales. We collected
data from restaurants within different niches, where a niche was defined by the restaurants returned for a
specific keyword, location and price range search combination.

For our project, we analyzed pizza places with a price range of $$ in Boston and pizza places with a price
range of $$ in New York City. Our goals were to define which features were most important for restaurants
to attain a high Yelp rating for these individual niches, then compare the differences between desired features
for pizza places in Boston vs New York.
