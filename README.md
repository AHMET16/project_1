# project_1

![This is an image]("images/https://www.google.com/search?q=gulen+ve+uzulen+yuz+tiyatroda&rlz=1C5CHFA_enUS941US941&sxsrf=AOaemvIL4ghxKcfdyADj842eqdlm9SvOag:1640819629996&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjjhL65kYr1AhWCdd8KHbH5BXoQ_AUoAXoECAEQAw&biw=976&bih=907&dpr=2#imgrc=hCAznynNMgetdM "Title is optional")

# Microsoft Movie Analysis 


#### Author: Ahmet Karaoglan 

### Overview 

This project represents a preliminary study of the entry into the microsoft film industry. The company, which is very new in this sector, made front studies by making use of the large database containing the data of movies such as IMDB, TMDB, ROTTEN TOMATOES. We decided to examine the director, genre and movie revenues. We determined which film genres had a more successful effect on the directors' revenues. Using this data, Microsoft can decide which movies it would be right to start with in its new project.

### Business Problem

Microsoft is the world leader in its field, but the film industry is also very new in terms of know-how, the company should decide how much budget it has outside of this project and decide on the film it will shoot. The results of the data and analyzes I have collected show the following. Genre and revenue data of the directors have determined the genre that provides the least risk for companies that have just started in the film industry, it seems that drama is the genre that gives the highest rating in the world and the film industry also wins the most awards. It would be more accurate to start the Microsoft drama movie field as well.

## Data Understanding
- Questions to consider:

###### Questions 1 Where did the data come from, and how do they relate to the data analysis questions?
The data is collected from Box Office Mojo, IMDB, Rotten Tomatoes, and TheMovieDB.org. The data has information about movie titles, genres, directors, actors, profits, release year.
 
 
 ###### Questions 2 What do the data represent? Who is in the sample and what variables are included?
 
 The data provides imdb there is 1000 movies data
 [IMDB](https://www.imdb.com/)
 [TMDB](https://www.themoviedb.org/)
 [Rotten Tomatoes](https://www.rottentomatoes.com/)
 

## Methods 

### Data Preparations

Questions to consider:

###### Questions 2 

How did you prepare the data?

Here are the datasets that I used for analysis:

IMDB-Movie-Data

###### Questions 3 Were there variables you dropped?

data.dropna(axis=0)

Questions to consider:

###### Question 2 Were there variables you dropped?

I dropped the following columns from the data:


Questions to consider:
    
    -firstly i got the top 1000 movies data from imdb
    -I dropped rows with missing data and duplicate.
###### Question 3 When you consider the problem of the workplace, which data did you decide to examine ?


-Genre

-Director

-Revenue


# Data Modeling

Questions to consider:
###### Question 4 How did you analyze or model the data?

I listed the different types of movies I identified the first 1000 genre the movies

Secondly, I wanted to find out whom Microsoft should work with for the best profit. 

###### Question 5 Which directors, writers or actors are deriving the most profitable movies and which of them have the best ratings?

###### Question 6 how did you iterate on your initial approach to make it better?

i used lambda function for Genre, I determined which genre are preferred

I described the genres, and determined which films the directors had grossed over.


###### Question 7 Why are these choices appropriate given the data and the business problem?

I think deciding the genres of the movie and whom to work with based on the profit and ratings is a good step for a first attempt at creating a new movie studio. This will give an general sense of the indsutry.


## Evaluation

Questions to consider

###### Question 8 How do you interpret the results?

we determined which tours were preferred and which directors represented these tours.
Considering the budget to be allocated to the microsoft film project, which genre and film should be preferred, more comfortable choices will be made as a result of these analyzes.
###### Question 9 How confident are you that your results would generalize beyond the data you have?

imdb, the most well-known web page of the film industry, here gives us the signals of what kind of film and with which director we should work with in the future.


## Conclusions 
Questions to consider:

###### Question 1 What would you recommend the business do as a result of this work?
         1-Action = 303,
         2-Adventure = 259,
         3-Sci-Fi =120,
         4-Mystery =106,
         5-Horror = 119,
         6-Thriller =195,
         7-Animation =49,
         8-Comedy = 279,
         9-Family = 51,
         10-Fantasy = 101,
         11-Drama = 513,
         12-Music = 16,
         13-Biography = 81,
         14-Romance = 141,
         15-History = 29,
         16-Crime = 50,
         17-Western = 7,
         18-War = 13,
         19-Musical = 5,
         20-Sport = 18

we have the numbers of the most preferred genre in the first 1000 movies

Genre and director should be preferred, taking into account the size of the microsoft film budget and the time he gave to the project.

If our budget is small and we have little time for the project, we should prefer the drama films and Christopher Nolan as the director, both drama film shooting costs are low and the best prizes go to this sector.





1-Christopher Nolan

2-Nitesh Tiwari

3-Makota Shinkai

4-Olivier Nakache

5-Martin Scorsese

6-Damien Chazelle







###### Question 10 What are some reasons why your analysis might not fully solve the business problem?

Global problems(epidemics, earthquakes, wars, etc.) may be the main reason, these problems affect all the work done and negatively affect your project, if microsoft is going to enter the film industry, it should take into account global problems and keep risk analysis in the foreground, the best genre, director, and a strong budget may not make you successful.


