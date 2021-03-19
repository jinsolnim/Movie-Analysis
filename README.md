# Movies for Microsoft
![Alt Text](https://media.giphy.com/media/8lKyuiFprZaj2lC3WN/giphy.gif)


**By**: Jinsol Cantrall
****


## Overview

What does it mean to be successful in business? How can you measure success? According to Google, 'Success is running a profitable firm that conducts business.' So in order for business to be successful, money is going to be the most important factor to measure the success.

Movies are one of our all time favorite entertainment businesses that have been growing since it was invented. This industry has been known for creating billions of dollars until today. According to the wikipedia, “The worldwide theatrical market had a box office of US$42.2 billion in 2019.”

 In this report, with the datasets from the we will take a closer look at the profitable factors to create a movie.

## Business Problem

Microsoft stakeholders have noticed their competitors creating original video content. In response, Microsoft has decided to create a new movie studio, but they are unfamiliar with the film sector. I have been given several datasets, and are asked to put together a report on the movie industry that will allow Microsoft producers to make informed decisions.

#### "What is a successful film?"
1. The most **profitable** - money
2. The most **popular** - ratings

##### Questions to ask:
* Question 1: Is it profitable to create film? 
* Question 2: Which genres of movies were popular? 
* Question 3: Does the large buget movie brings more money? 
* Question 4: Running time could be a huge factor of popularity of the movie?
***

## Data

Following datasets are used for analysis.

1. The Numbers (budgets)
2. iMDB (titles)
3. iMDB (ratings)
***

## Methods

Use ELT (Extract Transform Load) method to clean data
* Import data
* Apply Functions
* Group Data
* Check for duplicates
* Remove duplicates
* Recheck for duplicates
* Create Pivot Tables
* Deal with missing data (replace or drop)

Data Visualization with Seaborn and Matplotlib

***


## Results
### Question 1: Is it profitable to create film? 
- Yes, 72.2% of the movies passed break-even point

![graph1](./visualization/piegraph1.png)


### Question 2: Which genres of movie is popular? 
- Top 5 genres that were created were Drama, Documentary, Comedy, Thriller, and Horror
- Top 5 genres that were pouplar were Documentary, History, Biography, Music, and News 

![graph2](./visualization/g2.png)

### Question 3: Does the large budget movie brings more money? 
![graph3](./visualization/g3.png)

### Question 4: Running time could be a huge factor of popularity of the movie? 
![graph4](./visualization/g4.png)
- No. It has a very small correlation between popularity and running time


Average running time has been increasing over decades.

![graph5](./visualization/g6.png)





## Conclusions
Starting movie business seems not bad. As you can see, most movies(72.2%) made more than the budget. Highest net gross movies are not always the most highest average rate nor most reviewed. As far as genres, Comedy Drama seems like safest bet since both genres are popular genre. Comedies, Documentaries and Dramas have a lot of popular movies, in terms of pure numbers. But News, Documentaries and Music have a lot of popular movies, in terms of percentages.


## Repository Structure

```
├── data                                
├── images                             
├── Notebooks        
├── src
├── Visualization
├── DS_Project_Presentation.pdf         
├── Movie Analysis for Microsoft.ipynb   
└── README.md         
```
