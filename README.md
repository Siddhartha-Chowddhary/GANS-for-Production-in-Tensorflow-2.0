# GANS-for-Production-in-Tensorflow-2.0


# Instructions to train from scratch:-

UnZip Models and Numpy_File_Data  if you want to use it for experiment porposes or else go on with your on Data and Models by following     the steps below 
 1. Run Data_Loader.ipynb
 2. Run GANS_Model_v2.ipynb and change the Tensorflow 2.0  Dependencies to Tensorflow 1.14
 
 # How to increase the performance and quality of GANS:-
 1. Change the seed size to 20 for 13000+ images
 2. if you are using Celeba dataset then 100 should be good 
 
# Instructions to Deploy the Model for production:-


# Numpy_File_Data Folder :-
Contains Numpy array data file of Sports Car images you can make your own Numpy File using Data_Loader.ipynb

# Models Folder :-
Contains Trained Model which is trained on Sports car images you can create your own in verison Tensorflow 1.14 and use that model for Production 

# Notebooks Folder :-
Contains Data_Loader.ipynb & GANS_Model_v2.ipynb

# How to use GANS_Model_v2.ipynb for Production ?

1. Load in the Tensorflow 2.0 Dependencies
2. Load the Trained Tensorflow 1.14 or Tensorflow 2.0 Model 
3. Change EPOCHS = 10000, 60000 ... ===> EPOCHS = 1 
4. The very first trained Epoch output will be the production ready output  
