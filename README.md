# SMP-Binary-Image-Segmentation-Training
A google colab notebook to train any model available in the segmentation-models-pytorch library on a binary image classification task with data augmentation


## This is how you should be formatting the file structure ##

Code is included to augment the images by adding this such as rotation etc. which are then saved in the Train_Augment folder

Images should be in .jpg format

/content/Train
/content/Train/Images
/content/Train/Masks

/content/Train_Augment
/content/Train_Augment/Images
/content/Train_Augment/Masks

/content/Test
/content/Test/Images
/content/Test/Masks
