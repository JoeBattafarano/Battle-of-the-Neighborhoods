# Business Problem:
* Business (Audience 1): I want to expand my business to other locations in Seattle. However, I do not know what is the best location. Can you find other locations that fit our customer's price range, expectations, and interests?
* Individual (Audience 2): I want to work in Seattle, but I don't want to commit a large portion of my salary to rent. Can you find a similar neighborhood to my current while not compromising on my budget, needs, and interests?

# Data Sources:
* Neighborhoods: Scraped from https://en.wikipedia.org/wiki/List_of_neighborhoods_in_Seattle
* Latitude/Longitude: GeoPy
* Venues:
  * Closest Venues per Neighborhood: Foursquare Places API explore endpoint
  * Pricing and Rating: Foursquare Places API details endpoint
 
 # Modeling Choice and Features
 * Model: K-Means Clustering
 * Features: Venue Frequencies, Price Tier Frequencies, Average Venue Rating per Price Tier
 
 ## For more information on Data Understanding, Data Prepartion, Evaluation, and Beautiful Visuals please see the .ipynb files
 
 
 
