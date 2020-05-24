# NCAA To NBA

## Main Objective
  Trying to perdict the career of the next NBA draft - 2019, using web scraping

## Step 1 & 2- Scraping + Scrub

#### CreateDBup.ipynb
	Scraping from basketball-refernce NBA stats from 1980 season - table for regular season and playoff
	Data processing - creating a table of averages and total
#### Create_NCAA.ipynb
	Scraping from realgm NCAA stats from 2003 season
	Data processing - creating a table of averages and total
#### Draft.ipynb
	Scraping from basketball-refernce information about the NBA draft from 1989
	Examination of the data
#### Awards.ipynb
	Scraping from basketball-refernce NBA individual awards
#### Top100Prop.ipynb
	Scraping from nbaDarft mock draft to get 100 next propects
	Merging with data to create table of each player stat
	Examing the data

## Step 3 - Exploer 

#### ChangedNBA.ipynb
	Checking the progression(?) of the NBA from 1980 to our days
	Ploting different subjects -
		3PT to 2PT, height, PTS, eFG%
 #### Colleges.ipynb
	Giving a value to each college by the players succes in the nba
	Examing the data - using a formula based on player awards
#### OusideAmerica.ipynb
	Scraping a list of countries of players the played in the NBA from Wikipedia
	Finding succesful countries with the same formula we used in Colleges.ipynb
#### High_School_Europe.ipynb
	Examing the succes of players that didn't came from a college system

## Step 4 - Model

#### Clusters.ipynb
	Scaling the data
	Clustering the table to 5 groups using K_Means
	Examing the the groups - successfully spliting the players to 5 tiers - 
		Fillers, Role Players, Role Players\All Star, Hall of Fame, Legends

## Step 5 - Interpret

#### CorrNCAA_NBAGroup.ipynb
	Merging the 2 dataset - NBA and NCAA players
		Creating the table of players from 2003 - first season 
		Scaling the stats
  ##### Split the dataframe to
	  X- players stats
	  Y- player group
  ##### Trying to predict using Decision Tree & Naive Bayes
	  DT grade - 0.34
	  NB grade - 0.4

## Interpretion

#### We found what influence the most on player successful career
#### We can split the players into 5 tiers based on the information on NBA players
#### The accuracy of the prediction only based on the college stats isn’t working. There are too many “hidden” variables. Some of them we can’t see in analytics such as potential, work rate, etc.
#### Some more information is available in the web, but you have to pay for it maybe with that you can be more accurate
#### The NBA is becoming more mobile, more efficient, more widespread, more international – more ratings (?)
