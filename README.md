# Project title
We evaluated rainfall data for different cities in Asia in order to predict the best times of the year for agriculture and the best time for turism. After visualizing and studying the data, we decided to focus on two cities, Orissa and Kerala. These two cities are located in india and are known their production of food grains,  coconut, rubber, tea, coffee, pepper, areca nut, ginger, and cinnamon. These cities are not only known for their agriculture, but also for their beauty and turists attractions.


## Motivation

Our motivation to study these data was to find a pattern that would determine the best times for agriculture and tourism, thus enhancing the economy of these two cities.

## Tech/framework used

This game was built using

Rstudio
 
## Visualizing and explaining our results

**Below we have included a couple graphs with an explanation of what the graph means, the reasoning behind each one of these graphs lead to our CONCLUSION:**






This is a scatterplot of the annual rainfall in Orissa over the alst 100 years. First we took a look at our dataset and determined that the months with the most rainfall are March through September. As we can see in the picture, there is not really a pattern, but the more rainfall Orissa got in may and march, the more it rainned in June, July, and September.

![LINEAR REGRESSION](https://user-images.githubusercontent.com/58013489/70103649-b545f900-1609-11ea-8c8b-7933359b3938.png)
 
In the graph below we tested the accuraccy of our model by trying to predict the Rainfall in Kerala form 2010 - 2011 based on the annual rainfall from 2004 - 2009. As we can see, the ammount of rainfall has actually increased since 2009. However, there is not a significant correlation in the annual rainfall, so we decide to focus on the rainfall for each month.

![predict](https://user-images.githubusercontent.com/58013489/70103397-0e615d00-1609-11ea-9301-829e9c5eeb8e.png)


 
 
 
 
 
 
## Installation

**The libraries and packages that we had to install in order to properly analyze the data were:**

Install.packages party
library(tidyverse)
library(party)
install.packages("knitr")
install.packages("rmarkdown")
install.packages("forecast")

## How to use?

First you need to open the html, if you want to compile the project yourself in order to see the results step by step, click dowload code from the top right hand corder of the html file. Then, You will also need to download out dataset from github. Once the code is downloaded and the rainfall dataset has been set as the working directory, run each chunk one by one. Each chunk will have a brief explanation of what we are trying to accomplish. 



Insert pictures with examples

## Credits
 https://gluonhq.com/products/javafx/
https://docs.oracle.com/javase/tutorial/uiswing/layout/grid.html
Classroom textbook and previous codes
License
STU © Carlos Aybar De Los Santos , Biao Chen, and Aarmando MGhee


