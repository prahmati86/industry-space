# industry-space

The industry_space folder includes the edge lists of the undirected industry space network between years 1991 to 2015. 

ind1: 6-digit NAICS industry code

ind2: 6-digit NAICS industry code

weight: this variable is the actual weight of the links in the industry space which is calculated using Equation A2

transformed_weight: the original weights tranformed using ln(1/weight). The tranformed weights are considered when using the shortest path algorithm to calculate 
the industry-level digital proximities. 
