# DL4DR_2D_Prediction
A tool for prediction of IC50 via the upload models

requirements:  
python 3.6+   
keras>=2.3.1   
tensorflow>=2.2   
matplotlib>=3.1   


image_test -- directory contains all images that will be predicted   
MDA-MB-231.h5  -- the model that will be used (maybe updated in future)  

running the program in terminal:  
./dl4dr_image.cpython-37 image_test MDA-MB-231.h5

it will generate a log file in "image_test": MDA-MB-231.h5-log.txt
