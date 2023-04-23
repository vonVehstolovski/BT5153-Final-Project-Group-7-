# BT5153-Final-Project-Group-7
This is the Transformer Model code for the BT5153. This was built on Kaggle Notebook. Best to run on Kaggle Notebook to reproduce the results.

This repository contains the following:
1. The final running transformer model for the sign language video: "Final Transformer Model for ASL Videos.ipynb". This is best run in Kaggle Notebook withh GPU. 
2. The failed Google Colab transformer model: "Failed Colab Run of Transformer Model.ipynb"
3. Sampel Data files. The actual data size is 56G. Please refer to this Kaggle Competition for complete data: https://www.kaggle.com/competitions/asl-signs/data

  a. train.csv: the file which maps the parquet file names to the true sign label.
  
  b. sign_to_prediction_index_map.json: mapping of the sign to numeric order.
  
  c. 16069.zip: just a subset of the 16069 folder, containing 5 parquet files. The actual 16069 folder contains 4.8k files. 16069 is the participant ID of the ASL language videos. 16069 folder is one of the 20+ participants. 
