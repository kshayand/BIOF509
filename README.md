# Predicting ILD status from TCR V, TCR J, and HLA genes in Scleroderma Patients
Welcome to my Machine Learning (BIOF509) class project. In this repo you will find 
1) The jupyter notebook with my code. You ucan see information about each function as comments above the code blocl.
  You can download the notebook and run/modify the code as suits your needs. For help running a jupyter notebook, I recommend:
  https://www.anaconda.com/products/individual
2) A html file with my output. The html file has all the images and output from my script easily visible. 
3) An excel workbook containing my data. The workbook contains different sheets corresponding to different subsets of the data that I used. 

# Adapting this project for your own use:
- I recommend formatting your data into an excel workbook with the outcome as the first column and feature data in the next columns. The name of your workbook and the sheet name can be passed directly into the read_data() function.
- For RandomForestClassifier and GradientBoostingClassifier, I use many of the Sklearn's default values. If you have specific parameters to change, you can modify the notebook. The RandomForestClassifier is instantiated in the [ doStratifiedTest() ] (line 11) and the GradientBoostingClassifier is instantiated in the ][ doStratifiedGradientBoost() ] (line 10) function. 
