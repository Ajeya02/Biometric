# Emotion detection
Emotion Detection using Eiffiect Vit, Efficient Net B0 and 3DCNN. 
Note: The inference_threshold contains the plots to find optimal threshold and the training accuracy on the videos. The infernce_validation has the final obtained vaidation accuracy on the videos.
 ## Data Prepration
 The data prepration was based on [Selim Seferbekov implementation](https://github.com/selimsef/dfdc_deepfake_challenge#data-preparation)

 

 ## Restructure the data
 Split the data ino train, val and test folders
 use restucture.ipynb that restructures the data such that train (& val, test) has only images without subfolders

 ## To run the Models
 Change the paths in the .ipynb files to point to your data folders and run. The uses the saved weights and run the inferncing files.

