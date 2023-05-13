# Arabic Dialect Detection

This repository is to provide an application for detecting and identifying the arabic dialects using ML and DL models.

Demo: 

https://github.com/MohamedEssam7/NLP-Dialect-Detection/assets/52338861/d77723ef-0821-4795-91ef-673f384580bf

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
  ### 03 ML Model Training
   - Text representation using TF-IDF
   - Model selection
     - SVC F1 score of 82%
     - Lightgbm  F1 score of 75%
  ### 04 DL Model Training
   - Hugging Face AraBert accuracy 84%
  ### 05 Deployment
   - convert our model into ONNX model
   - Deploy with FastAPI

