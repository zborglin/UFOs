# **UFO Sighting Reports: An interactive html table**
Interactive Data Table Application
- html
- javascript
- bootstrap

## **Purpose** 
This web-based compatible tool displays UFO sighting data for enthusiasts to monitor and filter to study results by the following attributes:
- **Date of Observation** 
- **City, State, and Country the Observation was Reported In** 
- **Shape of the UFO** 
# 
The tool is configured to clearly display the information for interested users. Directions for how to use the filters is found below 

## Resources
- static/data.js

## How to Use Data Filters
### Unfiltered Data Table
![Unfiltered Data](https://github.com/zborglin/UFOs/blob/main/static/images/unfiltered.png)
### Filtered Data Table
![Filtered Data](https://github.com/zborglin/UFOs/blob/main/static/images/filtered.png)

## Results
Please reference the images above as you follow the filtering instructions 
1. The top image shows the unfiltered UFO sightings data table
- Filter input formats are given by showing a preview value for each filter field
- All data is shown in the data table as no filters are applied
2. The bottom image shows the application of a city filter for the data table
- "el cajon" is entered as a city filter
- Press enter to apply filter to data table and display the filtered data

## Evaluation of Application
1. **Drawback of Application Design**: The filter inputs require exact matches in order to return the associated data. If there are any typos or a different format is used, then the results might not show up when the user expects it to.
2. **Recommendations for Further Development**: In order to increase the quality of this tool, it is recommended that the filter input process be augmented to allow for partial completions and typos to still return the relevant information in the data table to increase ease of use of the tool. In addition, this tool can be improved by adding a web scraping application that automatically pulls new sightings data as they are reported into the table. 