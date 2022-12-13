# group_project_1
Questions:
1.    Do smaller dogs bark more?
2.    What are the life expectancies of different sized dogs?
3.    Is there a correlation between a dog's height and weight?

Step 2: Collecting the raw data to analyze
Data source:
a.    https://api-ninjas.com/api/dogs
b.    https://tmfilho.github.io/akcdata

Step 3: Processing the data
Cleaning Data

1.    Data from CSV was missing from API, run a try/except
2.    Cleaned out duplicates using pandas
3.    Grouped dogs by weight*
4.    API keys by every member of the group were generated to use in private. There are limitations on how much data can be pulled by the Dog API
5.    Loop algorithm was developed to cycle through and retrieve all the dog data
6.    Try-except code was used in order to filter our bad dog names or missing data
7.    Dataframes were built to collect and store the data
8.    Search for duplicates and removed them from the dataset
9.    Created new calculated averaged fields to best represent the data
10.    Created dog groupings to better analyze and summarize the data





Faceted Data by Size: Parameters set by American Kennel Club (AKC):: 4 sizes of dogs (Small, Medium, Large, X-Large).
Table 1: Size Facets

Size    Weight
Small    <= 22
Medium    22  < x < = 59
Large    59 < x < = 99
X-large    99 < x
Gender Inefficiencies: Gender size differences made faceting original data inefficient (29 inefficiencies). 
Solution: Average the weight of genders per breed to get congruent data.


Continue reading by seeing write-up doc
