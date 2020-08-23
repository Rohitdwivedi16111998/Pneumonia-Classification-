# Pneumonia Classification Using Chest X Rays -


This Kaggle Challenge aims to build a predictive model using which we can classify whether the patient has Pneumonia or not by Chest X Rays of the Patients. The Dataset is publicly available on Kaggle titled as "Chest X- Rays Penumonia".
The size of the data is 1 GB. There are three folders that are training, testing and validation. The Chest X Rays are classified into two categories that are normal and pneumonia.

# Prerequisites

 1) Understanding of Deep Learning Models
 2) Transfer Learning
 
# Dependencies

 1) Numpy Package 
     
     pip install numpy 
     
 2) Kaggle Package 
  
     pip install kaggle
    
# VGG19 Model 

  Run the VGG19Model.ipynb file to build the model. Save the model in HDF5 file format. 
  
# Prediction by VGG19 Model 

  Run the model evaluation file to load the save model and compute prediction on testing images. 
  
# Directly Compute Prediction 

  Training of model will take around 20-25 mins. If you want to directly download the model file. Visit here https://drive.google.com/drive/folders/1dqOZ_VX3bZ50XUly0zmaUB7lxq68YfpU?usp=sharing and download the model weights. Run the evaluation file to compute predictions. 
