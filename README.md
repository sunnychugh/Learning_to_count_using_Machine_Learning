# Learning_to_count_using_Machine_Learning
It involves building a Machine Learning model (e.g. a deep neural network) that processes an image containing elliptical, coloured blobs and correctly counts them amongst clutter in the form of coloured polygons.
 
 This problem has been framed by Aston University (all rights to them). For more details refer file ```Aston_MachineLearning_assessment.pdf``` in the directory.

The LR version (see ```shapes_dataset_LR.zip```) contains low-resolution 64x64 images, MR version contains mid-resolution 128x128 images while the HR version contains high-resolution 224x224 images such as the ones used in the ImageNet challenge. Due to the space limitation, MR and HR version images couldn't be uploaded. Although, the code is written according to the HR version of images. It can be altered easily as per the images resolutions. The zip folder can be extracted to see the images.

Code, comments about steps and chosing of hyperparameters are given in the python notebook: ```learning_to_count_object_detection_pytorch_1.ipynb``` 
