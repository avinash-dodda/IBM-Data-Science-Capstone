# The Battle of Neighborhoods
## Applied Data Science Capstone by IBM/Coursera
### Avinash Dodda - Aug 2019

## Data

Based on the criteria, Sarah has identified below data requirements and corresponding sources to perfom the analysis.

    
| Data                                             | Source                                                                                         |
 -----------------------------------------------   | -----------------------------------------------------------------------------------------------|
| List and Locations of Neighborhoods in Toronto   | [Boundaries of City of Toronto Neighborhoods](https://open.toronto.ca/dataset/neighbourhoods/) |
| Locations of Metro/Subway Stations in Toronto    | [Foursquare API](https://developer.foursquare.com)                                              |
| List of Restaurants in each of the Neighborhoods | [Foursquare API](https://developer.foursquare.com)                                              |
| Crime statistics of all the Neighborhoods        | [Neighborhood Crime Rates](https://data.torontopolice.on.ca/datasets/neighbourhood-crime-rates-boundary-file-) |

1. To start the analysis, the list and locations of all neighborhoods of Toronto are required. Sarah has identified that the City of Toronto Open Data Portal provides the list and location data of all 140 neighborhoods in Toronto.
2. Since connectivity to Downtown is a key factor, Sarah has decided to use the proximity of neighborhoods to Metro/Subway station locations. The locations of Metro Stations are extracted using **Foursquare API**
3. List of Restaurants in each neighborhood are also extracted using **Foursquare API**
4. For determining the safety level of each neighborhood, Sarah has identified the neighborhood level crime statistics from Toronto Police data portal 
