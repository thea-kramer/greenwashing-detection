
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
- Jupyter notebooks numbered according to the order of execution
- requirements.txt containing all required libraries, using command:
  
  `pip install -r requirements.txt`
- the datasets are NOT included for data protection reasons, add the two folders twitter_data and instagram_data to the repo

## Data files
For data protection, the 2 folders twitter_data and instagram_data with the necessary csv files to run the notebooks are not included. Request them by writing me an email, then you can paste twitter_data and instagram_data folders to the main directory where the notebooks are in.

## Running instructions
  
Here is an overview of the code pipeline and the respective data. For each Jupyter notebook (row in the middle), certain data files are used as input and certain ones are generated as output. This way, the notebooks can be run independently of each other.
 
![Data and Code Overview](https://github.com/thea-kramer/greenwashing-detection/blob/master/Overview_Code_Data.png?raw=true "Data and Code Overview")

For pure analysis results, it makes sense to run the Jupyter notebooks with the preceeding number 3 - 8. Within the notebooks, you find instructions on which variables to change and descriptions what is computed.

