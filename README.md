# Education in India

## About :

I was interested in knowing more about how the literacy rate 
in Indian states was affected and what factors could we work
on to help improve the literacy rate of different states.
I found some data from kaggle which contained census data
regarding the literacy rate in diffrent Indian states and the
education indicators, eg: No of teachers, no. of schools, etc.,
for Indian states and Union territories for 2015-16. Thus, using
that data, I tried to answer these 3 questions in depth: 

* Which states have the highest and the lowest literacy rates?
* How are the top 3 states different from the bottom 3 states and what factors can the bottom 3 states work on to increase their literacy 
rate? 
* Which class is the dropout rate maximum in ?

The last point above is not exactly a question, but I figure that it can be used to predict the literacy rate based on education indicators
each year as the literacy rate is only calculated once during census but the education indicators are calculated every year. Thus helping in
understanding how the literacy rate changes due to the change in education indicators.

I have also created a medium post on this analysis that can be found here : 
https://medium.com/@ishannangia/a-statistical-look-at-the-indian-literacy-rate-80a0e541ba7d

## Files/Folders :

1. data : This folder contains the datasets.
2. Education in India.ipynb : This is the jupyter notebook where all the analysis has been done. 

'Note: You can find more information about the dataset at
https://www.kaggle.com/rajanand/education-in-india'

## Process : 

I followed the CRISP-DM when working on the analysis:

1. #### Business Understanding: 

I wanted to answer the following questions:

* Which states have the highest and the lowest literacy rates?
* How are the top 3 states different from the bottom 3 states and what factors can the bottom 3 states work on to increase their literacy 
rate? 
* Which class is the dropout rate maximum in ?

2. #### Data Understanding:

I collected the relevant data from here : https://www.kaggle.com/rajanand/education-in-india

This data has the literacy rate of different Indian states and the education indicators of different states.

3. #### Prepare Data:

The data was already clean but to a lot of new features were made in order to answer the questions. There was a lot of data wrangling involoved.

4. #### Results:

As there was no model to use for prediction, the answers to my questions were as follows:

1. The top 3 states were Kerala, Lakshadweep and Mizoram and the bottom 3 were Bihar, Telngana and Arunachal Pradesh.
2. The difference in male and female literacy rates, rural population proportion and dropout rates from 8th to 9th class played a huge role in separating the top 3 and bottom 3 states
3. The dropout rates in different classes were explored and while the dropout rate for 6th class was the highest, more students had enrolled in class 4 than had dropped out.

5. #### Deploy:

A blog post has bee created on Medium here : https://medium.com/@ishannangia/a-statistical-look-at-the-indian-literacy-rate-80a0e541ba7d







