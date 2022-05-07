# industry-space

The IndustrySpace.csv file includes the edge lists of the directed industry space network between years 1991 to 2015. 

ind1: 6-digit NAICS industry code

ind2: 6-digit NAICS industry code

weight`year': this variable is the actual weight of the links in the industry space which is calculated using Equation A2

transformed_weight`year': the original weights tranformed using ln(1/weight). The tranformed weights are considered when using the shortest path algorithm to calculate 
the industry-level digital proximities. 

Please refer to the following paper for background information, and cite it in any written work that uses this data:

Rahmati, P., Tafti, A., Westland, J.C.,  and Hidalgo, C. 2021. "When All Products Are Digital: Complexity and Intangible Value in the Ecosystem of Digitizing Firms," MIS Quarterly (45:3), pp. 1025-1060. Available at SSRN: https://ssrn.com/abstract=3589188 or http://dx.doi.org/10.2139/ssrn.3589188
