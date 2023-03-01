## QM2 2023 - Group 11
## Content of this repository

### data_preprocessing
* Notebook on how we prepared the tweet before hydration: tweets_preparation.ipynb
* Notebook on how we removed the hydrated the unnecessary information from the hydrated tweets and added back the BERT label: reducing_tweets.ipynb
* Notebook on how we cleaned the stringency index data: cleaning_stringency.ipynb
* Notebook on how we cleaned the COVID data: cleaning_covid.ipynb
* Notebook on how we cleaned the crime data: cleaning_crime.ipynb
* Notebook on how we cleaned the tweets: cleaning_tweets.ipynb , in particular there was a number of 53 states where it should have been 50, this code was used to fix this matter
* Notebook on how we merged all our 4 dataset into on unique dataset: merging.ipynb

Sidenote: The cleaning and merging notebooks originiate from one notebook, they were separated to make their reading easier. If you encounter any error with the code when you try to run it, please use this notebook: all_cleaning_merging.ipynb

### data_analysis
* Notebook of our analysis and visualization: stats_regression.ipynb
* Notebook of the panel statistics and complementary analysis: panel.ipynb


### datasets
All the datasets used in the context of our project are available at: https://www.dropbox.com/scl/fo/jnyiu4wzr8yd5m73k8cnu/h?dl=0&rlkey=gmkup83ch0fd7wjof98lf395j

The labelled tweets IDs from the  Computational Data Lab for the Web and Society (CLAWS) based at Georgia Tech University are available at: https://www.dropbox.com/sh/g9uglvl3cd61k69/AACEk2O2BEKwRTcGthgROOcWa?dl=0

### streamlit
The purpose of using streamlit was show the trend following the social perception amidst covid 19. The categorization was made on per state basis to individually visualize the pattern of hate tweets, crimes, and covid cases/stringency index against time [covid 19].   

Following steps were taken to create the streamlit application: 
1. Data categorized by state was imported. 
2. Select Boxes were used as option to select state and covid measure type [cases or index] 
3. Line Charts were then used to plot the interactive graphs 
4. As an added step, the data for the whole of the US was also added as option to the select box, a number of preprocessing steps were made before the data was ready to be visualized.  

The next step was to deploy the streamlit application to Heroku: 
1. Heroku has number of options to deploy the application. 
2. GitHub method was selected, and data was first uploaded to GitHub and then Heroku was referred the repository for the deployment codes. 
3. The Procfile was used for configuration and running the streamlit application. 
4. Requirement.txt file was produced to import necessary libraries to Heroku. 
5. Finally the application was deployed on Heroku and a link to access the web application was generated
