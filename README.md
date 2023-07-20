# SpoofSense-Task

# NOTE: Please access the code from the google drive link given below. The model weights are not being uploaded on github due to the github file size limit. 
Google drive link.

https://drive.google.com/drive/folders/14wwPeCldt-8NS3VC-UswCjA57g4didZy?usp=sharing



Task: Image forgery detection

Dataset: 3 types of images have been provided. Authentic images, copy-moved forged, spliced-forged images

# Outputs

In this repository, implementation of state of the art models like VGG16, RESNET50, RESNET101 have been used to classify between forged images.

# FOLDER STRUCTURE
FinalSubmission.ipynb
SpoofSense.ipynb


To get the predictions on the testing dataset, please run the FinalSubmission.ipynb file by changing the 3 paths in the second cell of the jupyter notebook accordingly to the testing data file structure.
folder_path_authentic = "data\\test\\authentic"
folder_path_copy = "data\\test\\copy-moved\\images"
folder_path_spliced = "data\\test\\spliced\\images"
d

After changing the 3 paths, please run all the cells till you get the predictions at the end.

# Predictions 
0 - authentic image
1 - forged image 
