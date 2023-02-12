
# Greenwashing Analysis on Twitter and Instagram of the DAX40
#### Keywords: greenwashing, sustainability, NLP, SVM, data analysis, social media

This project analyses how sustainability is handled in social media communications of the DAX40 and how general their sustainable claims are.
The project is part of an interdisciplinary project between the informatics department at Technical University of Munich and the communication science department and Ludwig-Maximilians-university in Munich.

## General Information

**Contact:**      Thea Kramer, thea.kramer<at>tum.de

**Date of data collection:**  30.11.2022

**Language of data:** EN and DE

**Data sources:** Twitter API (research access) and Instagram API (Crowdtangle)

## Data and file overview
1. Jupyter notebooks numbered according to the order of execution. From "0_..." to "2_...", the data processing is shown, however they do not need to be rerun. "3_..." to "8_..." are for analysis and should be rerun, as they are interactive.
- `0_InstagramDataRetrieval.ipynb` and `0_TwitterDataRetrieval.ipynb`: Retrieving of the raw data
- `1_InstagramDataProcessing.ipynb` and `1_TwitterDataProcessing.ipynb`: Restructuring the Instagram/Twitter data, unpacking nested data
- `2_SustainabilityCalculation.ipynb`: calculating and adding sustainability labels for the data
- `3_Analysing.ipynb`: basic analytics like how many posts over time etc.
- `4_AnalysingStatistics.ipynb`: more progressed analytics like correlations and regression
- `5_Predicting.ipynb`: Machine Learning models for predicting the sustainability label or whether a sustainable post has general claims
- `6_SimilarityAnalyser.ipynb`: Similarity analyser of word vectors of the different datasets
- `7_TopicModels.ipynb`: Topic Model Generator for each dataset
- `8_WordDistributions.ipynb`: Word Cloud Generator

2. requirements.txt containing all required libraries, using command: `pip install -r requirements.txt`
  
3. the datasets are NOT included for data protection reasons, add the two folders twitter_data and instagram_data to the repo

## Data files
For data protection, the 2 folders twitter_data and instagram_data with the necessary csv files to run the notebooks are not included. Request them by writing me an email, then you can paste twitter_data and instagram_data folders to the main directory where the notebooks are in.

Important data files:
Per folder twitter_data and instagram_data, you will find multiple csv files. Most important are the following 2:
- `posts_processed.csv`: For each folder respectively, it shows the complete dataset as explained in the codebook
- `green_posts_processed.csv` The same as `posts_processed.csv`, but filtered to only contain posts about sustainability

## Running instructions
  
Here is an overview of the code pipeline and the respective data. For each Jupyter notebook (row in the middle), certain data files are used as input and certain ones are generated as output. This way, the notebooks can be run independently of each other.
 
![Data and Code Overview](https://github.com/thea-kramer/greenwashing-detection/blob/master/Overview_Code_Data.png?raw=true "Data and Code Overview")

For pure analysis results, it makes sense to run the Jupyter notebooks with the preceeding number 3 - 8. Within the notebooks, you find instructions on which variables to change and descriptions what is computed.

