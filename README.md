# Words_Spoken_in_a_Movie

## Problem Statement
Hollywood has been trailed with gossip that men are given more words to speak in most movies. 
According to this article, https://pudding.cool/2017/03/film-dialogue/, data was collected to show the amount of words spoken by each gender in a movie and which gender spoke the highest amount of words in a particular movie.
The objective is to check if the Lead gender can be predicted using the other parameters such as year, number of words, and so on.

## Data
| Parameter          | Description |
| :---:              | :---:       |               
| Number_words_female | Number of words spoken by females in the movie |
| Total_words | Total words spoken by both male an female |
| Number_of_words_lead | Number of words spoken by the lead act|
| Difference_words_lead_co_lead | Difference between words spoke by the lead and co-lead|
| Number_of_male_actors | Number of male actors in the movie |
| Year | The year the movie was made |
| Number_of_female_actors | Number of female actors in the movie |
| Number_words_male | Number of words spoken by males in the movie |
| Gross | Amount made from the movie |
| Mean_Age_Male | The average age of the male actors |
| Mean_Age_Female | The average age of the female actors |
| Age_Lead | The age of the lead actor |
| Age_Co_Lead | The age of the co-lead actor |
| Lead | The gender of the lead actor  (Male/Female)|

## Method Used
I used the decision tree classifier.
The accuracy of the prediction is approximately 79.5%
