# Arabic Dialect Detection

This repository is to provide an application for detecting and identifying the arabic dialects using ML and DL models.

Demo: 


## Project Pipline:
  ### 01 Data Fetching
   - used SQLite connection and pandas to perform a join query and save the result in a dataframe.

  ### 02 Dara pre processing
   - Preprocessing has a pipeline that applied to our fetched dataset:
     - Removing Punctuations
     - Removing Symbols
     - Removing Emojis
     - Removing Diacritics
     - Removing Non-Arabic Characters
     - Removing Repeated
     - Apply Lemmatisation
  ### 03 ML Model
   - Text representation using TF-IDF
   - Model selection
     - SVC F1 score of 82%
     - Lightgbm  F1 score of 75%

