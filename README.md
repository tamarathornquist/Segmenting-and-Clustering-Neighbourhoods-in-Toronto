# Segmenting-and-Clustering-Neighbourhoods-in-Toronto
In this individual assignment I need to cluster Neighborhoods in Toronto, Canada by venue category. To this aim I first access the Wikipedia page to collect information on Postal codes, Boroughs and Neighborhoods in Toronto, Canada. The collected information is saved as a dataframe. Then, I clean the data and assign the latitude and the longitude coordinates of each neighborhood. I keep only the neighborhoods in Downtown Toronto and use the Folium library to visualize the neighborhoods on the map. Further, I make RESTful API calls to Foursquare to retrieve data about venues in different neighborhoods in Downtown Toronto. Finally, I cluster neighborhoods by the venue occurrence using k-means clustering. Clusters are visualized using the folium library. 
