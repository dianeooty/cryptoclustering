# cryptoclustering
This is my Module 19 Challenge for my Data Analytics and Visualization Boot Camp.  The objective is to utilze Python and unsupervised learning to determine if the crytocurrences are affected by price changes over 24-hour or 7-day periods.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
Using the data found in resources for crytocurrencies, I found the best k values with the scaled data and PCA data.  The original data was first scaled using StandardScaler() module and then the k and inertia values were used to display the elbow curve.  Fromt the elbow curve, we can determine the best k value to use for the model.  A scatter plot was then displayed to identify the clusters.  For the PCA data, a new dataframe was created with the PCA values before finding the k values.  Ocne the k and inertia values were generated, another scatter plot was displayed for visualization.  The results were then compared to find which method produced a better visualization for the clusters.


## Technologies Used
- Python
- Pandas
- Unsupervised Learning
- hvPlot
- scikit-learn

## Screenshots
![Example screenshot](./img/screenshot.png)

## Project Status
Project is complete and no longer being worked on.

## Acknowledgements
- Many thanks to my instructional team and tutor, David Chao.


## Contact
Created by Diane Guzman
