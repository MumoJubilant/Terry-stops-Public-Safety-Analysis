# Terry-Stops Public Safety

## Project Overview 
n Terry v. Ohio, a landmark Supreme Court case in 1967, the court found that a police officer was not in violation of the "unreasonable search and seizure" clause of the Fourth Amendment. Thus was born the notion of "reasonable suspicion", according to which an agent of the police may  temporarily detain a person. Terry Stops are stops made of suspicious drivers.
We aim to build a classifier to predict whether an arrest was made after a Terry Stop. 

## Data Understanding
The dataset source was from a website data.seattle.gov in a file named Terry stops. 

The data is grouped into categorical data which includes a record of:  
Subject Age Group                    Frisk Flag 
Subject Gender                       Arrest Flag    
Subject Race                         Stop Resolution   
Officer Gender
Officer Race  

## Objectives
### Main Objectives
* I.	Build a classifier to predict whether an arrest was made after a terry-stop 
* II.	Investigate whether there is any data that plays a role in making arrests
* III.	To evaluate and improve models used in predicting arrests
 
### Specific objectives
* Which features are identified as relevant for the binary classifier, considering factors like age, race, arrest flag, gender and frisk flag?
* How do arrests vary concerning different features, such as race, gender and age?
* What is the outcome of the Data Analysis in terms of understanding the distribution of key variables and relationships?

## Modelling.

### Logistic Regression
When you want to apply this to a binary dataset, what you actually want to do is perform a classification. In our case, we want to fit a logistic regression model to Target using Age, Race, and Sex. Since Target, Race, and Sex are categorical, they need to be be converted to a numeric datatype first,fit the model and then model evaluation 
## Training model with Logistic regression

Train data- Mean Squared Error Train: 0.1025

Test data - Mean Squared Error Test: 0.1047

## Training model with Decision trees
The accuracy of the model shows that it can predict the data 90% correctly

# Recommendation and Conclusions
## Recommendation.

Check on the male gender of the black American and White races
Collect information on the reasons for Arrest  to have better understanding of arrests
Calculating over the population to get a sense of how the different parameters are affected

## Conclusions
The different information affecting the arrest during the terry stops have made the models come together in harmony. Logistic regression and decision tree classifier were used to make the model predict the data which showed  a 90% accuracy. There was some imbalance in the data due to some nun values but were to be rectified by using ensemble methods.
Most of the classes were biased, as leaning to one group of people i.e Male, White and Black or African American
