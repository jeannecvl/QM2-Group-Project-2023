## qm2_group_11_2023
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

The labelled tweets IDs from the CLAWS are available at: https://www.dropbox.com/sh/g9uglvl3cd61k69/AACEk2O2BEKwRTcGthgROOcWa?dl=0

### streamlit
