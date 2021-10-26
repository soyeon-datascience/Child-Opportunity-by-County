# Which one gives more opportunity to children: City vs Suburb?
This analysis is centered around an exploration in the opportunity in different parts of the US. Opportunity can be a hard thing to define and changes drastically from culture to culture. We explored opportunities in three main facets: Livability, Economics, and Education. Trying to answer various questions from the perspective of the entire continental United States would be a daunting challenge. Many academics try to focus on this overwhelming task. Our analysis could help to provide a starting point. As such, we have decided to look at how opportunity varies among some of largest TOP 4 cities in the United States: Los Angeles, Philadelphia, New York, and Houston. These three main categories will be broken down into smaller sub-categories to more accurately depict the variance among the four major cities and their surrounding suburbs. 

## Data
The data set comes datadiversity.org specifically the child opportunity index with each individual observation being a census tract in 2015 that relates to a neighborhood. It has 146,112 rows and 38 columns. The data and the data dictionary are available [here](https://data.diversitydatakids.org/dataset/coi20-child-opportunity-index-2-0-database/resource/f16fff12-b1e5-4f60-85d3-3a0ededa30a0).

## General Approach
1. Clean and extract relevant data features
2. Address missing and unbalanced data
3. Data Visualization
4. Use K-means clustering to grouping counties

## Results
1. The first topic is the livability aspect of a city and its suburbs. In this Livability indicates the sum of the factors that add up to a community’s quality of life. Except New York state, city shows the highest livability.
<img width="1154" alt="Screen Shot 2021-10-25 at 10 49 21 PM" src="https://user-images.githubusercontent.com/92895639/138805867-5c04ad80-d0c1-466b-ae15-6c8e299826cf.png">

2. We compared each counties' median income. The interesting point here is that except New York state, the median income of city is lower than each state's average.
<img width="1154" alt="Screen Shot 2021-10-25 at 10 49 43 PM" src="https://user-images.githubusercontent.com/92895639/138805890-ead4e335-4880-4e71-b733-a1620f425ad5.png">

3. These graphs show third grade students' reading and math scores. Interestingly, the reading and math scores of children living in cities are smaller than average, except in New York state. 
<img width="1154" alt="Screen Shot 2021-10-25 at 10 50 09 PM" src="https://user-images.githubusercontent.com/92895639/138805907-79a8a617-be6b-4ba8-9c9e-a3fdd7e52050.png">

4. This is the result of K-means clustering. We got 3 groups. The first group consists of Staten Island, Orange, Harris, Vertura, Montgomery, Bucks, Delaware, Fort Bend and Chester. The second group is composed of Philadelphia, Kern, Liberty, Waller, and San Bernardino. The last group is Bonx, Los Angeles, Brooklyn, Manhatten and Queens. It turns out that the first group has the biggest opportunity for children. They have overall good scores on every section. Only Harris from Texas belongs to this group.
<img width="1154" alt="Screen Shot 2021-10-25 at 10 47 42 PM" src="https://user-images.githubusercontent.com/92895639/138805646-c4d4806b-362a-42ca-9268-74f278e2b316.png">

## Values
This can help distribute children's opportunities equally to all counties.

## Contributors
Soyeon Park, M.S. in Data Science Candidate  
Vanderbilt University  
soyeon.park@Vanderbilt.Edu  

Tonnar Castellano, M.S. in Data Science Candidate  
Vanderbilt University  
tonnar.castellano@Vanderbilt.Edu  

Ty Painter, M.S. in Data Science Candidate  
Vanderbilt University  
ty.d.painter@Vanderbilt.Edu  

Jay Kim, , M.S. in Data Science Candidate  
Vanderbilt University  
jay.kim@Vanderbilt.Edu  
