# Heart Failure Prediction
####  A Streamlit Contact tracing web application using Unsupervised Learning method  
https://share.streamlit.io/randell-janus/heart-failure-prediction/main/app.py  
  
  
![](cslogocropped.png)
  

## Dataset Source  
The dataset is a randomly generated file that is suppose to resemble an actual Travel History data of people that Contact tracing teams are using.  

## Objective  
With the randomly generated user ids and travel history data on a given time, predict who might actually have physically contacted each other through the use of density based clustering and data visualization.  

## Model Used
*  Density-Based Spatial Clustering of Applications with Noise (DBSCAN) - to make a model all you need is a function to calculate the distance between values and some guidance for what amount of distance is considered “close”. 

## Web App Features  
**Made with Streamlit**
* Sidebar Directory  
  * Home Page  
    * Contains the logo and a short description of the project.
  * Visualization Settings (Available while on the Contact-Secure page)
    * Contains a selectbox of user input chart types, and specific chart settings.
  * User Guide Page
    * Provides snapshots of the actual functionality of the application.   
    * Contains a step by step procedure on how to use the application.  
  * Contact-Secure
    * File Selection or Uploader (2 sample datasets provided).
    * Text input area for entering names of person of interests based on the chosen dataset.
    * Dataframe with filtering options based on the dataframe series.
    * A chart area based on the selection on the sidebar.
## Column Values
* id = names of users that are present in the same travel log data.
* timestamp - specific date and time of users
* latitude and longitude - global positioning location of the user.
    
