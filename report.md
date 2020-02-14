# Crime Analysis for Neighborhoods in Vancouver

## Introduction:

As everyone knows, Vancouver is one of the best place to live in. But which Neighbourhood should you choose and which characters should you consider? Well, most people may say price and safety! Well, there are a lot of websites that can help you to find houses under the budget very easily. So, this project will help you to find how safety that house is.


![alt text](https://www.globalmicrobialidentifier.org/-/media/Sites/gmi/News-and-events/2020/Vancouver-700.ashx?h=259&la=da&mw=460&w=460&hash=E269E3BFB70D7E32714BAC63D58A609AEED6A45E/to/img.png)  


In details, it will give you Neighbourhood guides in Vancouver based on the crimes reported in each Neighbourhood and clustering those Neighbourhoods into different groups. 




## Data:

In this report, two datasets will be used. The first one is the crime.csv which includes all crimes reported in Vancouver. It also shows the detail of each crime such as: crime type, date, and Neighborhood. This data is directly download from Kaggle, https://www.kaggle.com/agilesifaka/vancouver-crime-report


The Second dataset is the location data, which combined with a list of Neighborhoods and their GPS location. When I’m doing the research, there’ no direct files that contain this information, so I manually create a Location.xlmx file getting the location data from Wikipedia. The purpose of getting this location data is helping to combine the crime data with the Foursquare location data.


### Data CleanUp:

Based on the Vancouver Neighborhoods that identified in Location.xlsx dataset, some rows in crime.csv will be deleted (ie. rows that have Neighborhood values: ‘Musqueam’, ‘Stanley Park’, or ‘NaN’).

Also, in Neighborhood column of crime.csv table, ‘Central Business District’ will be changed to ‘Downtown’ just for convenience. 



