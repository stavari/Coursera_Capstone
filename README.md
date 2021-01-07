## This report will be targeted to stakeholders interested in opening a Greek restaurant in London, UK.
### The goal of our project is dual:
1. Find out if opening a Greek restaurant in the center of London is a right choice
compared to opening a restaurant of a different cuisine. Our decision will be based
on analyzing the number of restaurants per cuisine.
2. Find the best location to open the restaurant. The candidate locations will be
calculated based on the distance from other Greek restaurants, the number of
restaurants in the vicinity and finally the distance from the center of London.


### Data
In this project we will mainly use Venue & Geographical data in order to reach our
conclusion. We will use:
- Google Maps API to obtain the coordinates of the center of London and the coordinates of our segmented candidate areas.
- Foursquare API to get information about the existing restaurants in the area.
- Mainly the data that will be useful to us will be location coordinates and cuisine type of every restaurant in the area.
- skgrange.github To get a JSON file containing the Borough borders of London.

### Methodology
Our goal is to find some promising locations for a Greek restaurant. These are the steps to
reach our conclusion
- Locate a low-density area close to the center of London
- Locate promising locations inside the chosen low-density location
- Cluster the locations using K-means
- Find the addresses of the centers of these clusters
