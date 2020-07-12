# travel audience Data Science Challenge

## Goal
Using provide data, build a binary classifier to accurately predict the probability of a user to book based on previous search events.

## Install dependencies
``` 
pip3 install -r requirements.txt 
```

## Running code
All code for this exercise is contained in the __travel_audience_classifier.ipynb__ notebook for simplicity. After installing requirements.txt, you can start the Jupyter notebook with ``` jupyter notebook ``` command and open the notebook.

## Approach
The data set provides history for each user at an event-level. The classifier was built in order to consume data at this granularity in order to predict a user's likelihood to book at a given _point of time_. As a given user's behavior can change between searches, it's likely the case that their probability to book changes as well. All search-level features relate to the context of what was searched and are not dependent on the user. All user-level features relate to the context of a single user's search history. 

I have included the data for this exercise in the repo so that the workbook can be ran by cloning.
