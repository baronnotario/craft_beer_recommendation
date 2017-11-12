=============================================================================================
# Craft Beer Recommender

### FMP Alexandra Baron & Alejandro Notario

### Data Science Master. KSchool 4th Edition
=============================================================================================

# Description:

#### The main idea of this project is to develope a recommender engine to help craft beer sellers to recommend beers to their customers and therefore to sell more stuff. It has been tried to make web scraping asking for API's ay some websites as "Ratebeer", "Beeradvocate", but it was slow to build an important dataset with queries limitations so eventually it was got a .txt file from Beeradvocate from a Stanford University website with lots of records. From this:

=============================================================================================

## Steps:

### Data building and cleansing

#### This work can be found at Data folder. It has been got a final dataframe from a 2 columns .txt file to use testing code deceloping the recommender engines included in this repository, as well as study data structure and analyze it. Tasks and steps are described in a README included in this Data folder as well as the manual to run the notebooks inside.  

### Developing recommender engines:

#### It has been thought to consult different resources to get knowledege and start to program. It is for this reason, the structure of the Recommender Engine Folder has different ways to approach this target. Notebooks topics are decribe in README included in this Recommender Engine Folder.

=============================================================================================

## Conclusions:

#### The raw data was huge but it seems it is not enought to get a reliable recommender engine. This is becasue it is missed share data, it means more ratings, more users, and more beers had by users, there are lots of different beers... This is an issue which come from work with a static dataset from a few years ago. It is predictable it is going to improve becasuse of obtaining more and more data as well as loads of websites like Amazon, Alibaba, etc.
#### Anyway, the models work, but next target is to improve accuracy

=============================================================================================

## Pending tasks:

#### It has been wanted to program NLP to use the text review column which contains users comments to transform them in numerical rating code and use it in some model.

#### It has been wanted to make a webservice application using either Flask or Werkzeug to visualize the drop down lists of the 3 engines it have been made which have this application and show the prediction results.

#### Maybe an improvement would be to segment the dataset by styles to make micro recommender engines only for the most popular/had styles

#### All of them are a matter of time.

=============================================================================================



