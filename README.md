# IBM Capstone Data Science Project

This repository has been created for the submission of project files. 

## Capstone Project - The Battle of Neighbourhoods 

### Introduction/Business Problem section:
- The demographics of New York City indicate that it is a metropolis that is broad and ethnically diverse. It is the largest city with a long history of international immigration in the United States. In 2014, New York City was home to about 8.5 million residents, accounting for about 40 percent of the population of the state of New York and a significantly smaller proportion of the metropolitan area of New York, home to around 23.6 million. The city has been rising faster than the area over the last decade. The New York area continues to be the leading metropolitan gateway for accepted legal immigrants to the United States by far. New York City has also been an important entry point for immigrants; the word "melting pot" was coined on the Lower East Side to describe heavily populated immigrant communities.

- In New York, as many as 800 languages are spoken, making it the world's most linguistically diverse region. While there are areas in the outer boroughs in which up to 25 percent of people speak English as an alternative language and/or have little or no fluency in English, English remains the most spoken language. In communities such as Flushing, Sunset Park, and Corona, English is less spoken. With its diverse community, numerous food products are available. In New York City, there are several restaurants, each belonging to various categories, such as Chinese, Indian, and French, etc.


### Target Audience:
- A customer who is an immigrant in the New York city or a normal person who likes to explore different cuisine. Customer wants a good recommendation for the Indian restaurant which provide the best taste.

### Success Criteria:
- We should help to make the best choice for the below points by listing and visualizing all major parts of New York City that has great Indian restaurants.
  - what is best location in New York City for Indian Cuisine?
  - which areas have potential Indian Restaurant Market?
  - which all areas lack Indian Restaurants?
  - which is the best place to stay if you prefer Indian Cuisine?
 
 ### Methodology:
 
 1. Find all venues for each neighbourhood using Foursquare API.
 2. Filter out all venues with Indian restaurant for further analysis.
 3. Next using Foursquare API, find the Ratings, Tips, and Number of Likes for all the Indian Restaurants.
 4. Consider all the neighbourhoods with average rating greater or equal 9.0 to visualize on map.
 5. Visualize the Neighbourhoods and Borough based on average Rating using python’s Folium library.

### Result:

From analysis main research results are:
- Greenwich Village (Manhattan), Tribeca (Manhattan), West Village (Manhattan) are some of the best neighborhoods for Indian cuisine.
- Manhattan have potential Indian Restaurant Market.
- Bronx ranks last in average rating of Indian Restaurants.
- Manhattan is the best place to stay if you prefer Indian Cuisine.
