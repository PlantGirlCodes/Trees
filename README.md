# MillionTreesNYC

NYC has committed to having 1 million trees throught this public private initiative.
Trees have some many benifits, chief among them: the sequester carbon, filter air pollution, provide shadema adn have roots taht prevent erosion. 

NYC conducts a tree census to moniotr its progress. 
This dataset will analyze the data in the 2015 Tree Census. 

Trees: Kaggle
https://www.kaggle.com/datasets/new-york-city/ny-2015-street-tree-census-tree-data https://www.nycgovparks.org/trees/treescount

Trees: NYC open data
https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh

https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/pi5s-9p35

API Endpoint
https://data.cityofnewyork.us/resource/5rq2-4hqu.json
https://data.cityofnewyork.us/resource/uvpi-gqnh.json
More Info on Census

https://www.nycgovparks.org/trees/treescount

Tree Census Summary
Third street tree census
2,241 volunteers
Number of Trees: 666,134
City Blocks: 131,488
Volunteers completed 34 percent of the census
Park trees are not included in the cesus

Data Dictionary
https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh
tree_dbh Diameter of the tree, measured at approximately 54" / 137cm above the ground
curb_loc Location of tree bed in relationship to the curb
steward Indicates the number of unique signs of stewardship observed for this tree
guards Indicates whether a guard is present, and if the user felt it was a helpful or harmful guard
sidewalk Indicates whether one of the sidewalk flags immediately adjacent to the tree was damaged, cracked, or lifted
root_stone Indicates the presence of a root problem caused by paving stones in tree bed
root_grate Indicates the presence of a root problem caused by metal grates in tree bed
root_other Indicates the presence of other root problems
trunk_wire Indicates the presence of a trunk problem caused by wires or 10. rope wrapped around the trunk
trnk_light Indicates the presence of a trunk problem caused by lighting installed on the tree
trnk_other Indicates the presence of other trunk problems
brch_light Indicates the presence of a branch problem caused by lights (usually string lights) or wires in the branches
brch_shoe Indicates the presence of a branch problem caused by sneakers in the branches
brch_other Indicates the presence of other branch problems
postcode Five-digit zipcode in which tree is located
community board Community board in which tree point is located borocode
Code for borough in which tree point is located: 1 (Manhattan), 2 (Bronx), 3 (Brooklyn), 4 (Queens), 5 (Staten Island)
cncldist Council district in which tree point is located
st_assem State Assembly District in which tree point is located
st_senate State Senate District in which tree point is located
boro_ct This is the boro_ct identifyer for the census tract that the tree point falls into
latitude Latitude of point, in decimal degrees
longitude Longitude of point, in decimal degrees
x_sp X coordinate, in state plane, in feet
y_sp Y coordinate, in state plane, in feet

Some Key Findings from my analysis: 
* There are 683788 trees in the 2015 Tree Census
* There are 101390 blocks in the 2015 Tree Census
* There are 132 tree species in the 2015 Tree Census

![image](https://user-images.githubusercontent.com/84110998/235822746-2d6de489-a8f4-494d-b3e8-69e1d6dbee0c.png)

![Tree status by boro](https://user-images.githubusercontent.com/84110998/235822791-906602f8-0135-4913-92de-b72676c6b287.png)

After some initial EDA I selected 15 out of the original 41 I would use and also filtered for trees that were alive.

![image](https://user-images.githubusercontent.com/84110998/235823407-f1f7161e-2433-4c84-b7d3-910885b5b589.png)

The species London Planetree is most frequent across the entire dataset and with the greatest amount in brooklyn.
Since we are just coming out of cherry blossom season - queens has the most cherry trees  

Queens has the most trees over all the boros
![image](https://user-images.githubusercontent.com/84110998/235823680-b8116e73-ff87-43fb-a1bf-587016a2e81e.png)

I live in the zip code with the most trees in manhattan
![image](https://user-images.githubusercontent.com/84110998/235823756-da8e49f6-b340-48de-aac5-246c40510fba.png)

Phase 2 of this project
* will compare an earlier tree census with the 2015 and compare growth rate of trees by boro and zip

Phase 3 of this project will incorporate census data related to population and income


