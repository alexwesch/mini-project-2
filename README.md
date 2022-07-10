# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
Project goals is to become more framilar with API calls 

## Process
### Register for API access for the three sources. Read documentation for url and endpoints. 
### Pass authentication and access API.
### Parse JSON API results for relevant keys. If relevant keys are not present, look at documentation for specific API calls to get the API to return the desired result.
### Create for look to go the JSON API results and store relevant results in dictionary
### Covert dictionary to dataframe
### Use SQLite3 to create database from dataframes

## Results
Yelp seemed to have the highest quality of results. The results from Yelp most accurately represented the currently available business in the area, with newly openned businesses appearing more frequently. Google and Foursquare results contained comparitively a significant proportion of defunct businesses in their listings. Both Yelp and Foursquare returned the maximum number of listings allowed from a single call of their respective APIs, at fifty each. Google API returned twenty results, but 
Google had the highest number of reviews, possibly because they were aggregating from other sources. 

## Challenges 
All of the APIs handled authentication differently. Yelp required the string 'BEARER ' before the API key, and Google would not accept the API key as a authentication header.

## Future Goals
I would have made a function that would take a query keyword, then go through the josn from tha api and add the values for that keyword to a dictionary. 