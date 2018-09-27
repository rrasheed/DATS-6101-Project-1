# DATS-6101-Project-1

## Overview
This data was pulled from Rush Kirubi's Kaggle repository called "Video Game Sales with Ratings". 
URL to kaggle page: https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings/home

## Data
Motivated by Gregory Smith's web scrape of VGChartz Video Games Sales, this data set simply extends the number of variables with another web scrape from Metacritic. Unfortunately, there are missing observations as Metacritic only covers a subset of the platforms. Also, a game may not have all the observations of the additional variables discussed below. Complete cases are ~ 6,900

### Attributes:
Name - Name of the game
Platform - Console on which the game is running
Year_of_Release - Year of the game released
Genre - Game's category
Publisher - Publisher
NA_Sales - Game sales in North America (in millions of units)
EU_Sales - Game sales in the European Union (in millions of units)
JP_Sales - Game sales in Japan (in millions of units)
Other_Sales - Game sales in the rest of the world excluing NA, EU, and JP
Global_Sales - Total sales in the world (in millions of units)
Critic_score - Aggregate score compiled by Metacritic staff
Critic_count - The number of critics used in coming up with the Critic_score
User_score - Score by Metacritic's subscribers
User_count - Number of users who gave the user_score
Developer - Party responsible for creating the game
Rating - The ESRB ratings
