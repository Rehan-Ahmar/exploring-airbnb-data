# Exploring Airbnb open data following CRISP-DM methodology

This project was created as part of Udacity's Data Scientist for Enterprise nanodegree. Here I have analyzed [Seattle Airbnb Open Data](https://www.kaggle.com/Airbnb/seattle/data) following CRISP-DM methodology. Airbnb data for other cities have the same format. So the same understandings and code can be applied to any other Airbnb dataset.

The three business questions which I have tried to answer in this project are as follows:
- What is the seasonal price trend of Airbnb listings in Seattle? When are the most expensive and cheapest times to visit Seattle?
- How does price of Airbnb listings vary in different neigbourhoods?
- What are the most important factors influencing the price of Airbnb listings?

## Requirements:
Environment: python 3.6
Libraries Used : numpy, pandas, matplotlib, seaborn, sklearn

## Content
The analysis is divided into 4 files. The name of the files are self-explanatory.
- **Business and Data Understanding.ipynb**
- **Question 1 - Seasonal price trend.ipynb**
- **Question 2 - Price trend by neighborhood.ipynb**
- **Question 3 - Factors influencing price.ipynb**

## Conclusions
- Prices of Airbnb listings in Seattle are highest from July to September. The cheapest time is at the start of the year from January to March.
- The most expensive neighbourhoods in Seattle are Downtown, Magnolia, Queen Anne, Cascade and West Seattle. 
  Capitol Hill and Downtown neighbourhoods have highest number of listings.
- The most important features which influence prices of Airbnb listings in Seattle are bedrooms, accommodates, bathrooms, beds - all indicating the size of the listing. Room type(Entire Apartment/House, Private Room or Shared Room) and reviews per month are also important features. Location also plays an important role.
  The most important amenities influencing price are Family/Kid Friendly, TV, Indoor Fireplace, Elevator in Building, Hot Tub, Gym and Kitchen.

For a more detailed non-technical discussion, check out [my blog post](https://medium.com/@rehan.ahmar/analyzing-airbnb-open-data-following-crisp-dm-methodology-afbc7b1a9b64).

## Acknowledgements
Thanks to Airbnb and Kaggle for the data, and Udacity for course meterial.
