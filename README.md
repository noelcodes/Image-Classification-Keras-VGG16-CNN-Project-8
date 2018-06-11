# [Home Page](https://noelcodes.github.io/)

The pre-trained networks (VGG16, VGG19, ResNet50, Inception V3, and Xception) have been fully integrated into the Keras core. No need to clone down a separate repo anymore. These implementations can be found inside the keras applications sub-module.
https://github.com/keras-team/keras/tree/master/keras/applications

# Image-Classification-Keras-VGG16-CNN-Project-8
I attempted to train a model using VGG16 architure on my custom images 13 classes funitures.
For some reason, results is terrible, and very hard to train due to long training time.
The idea is to remove the last layer, and add my own dense layer with 13 outputs.  

CNN_VGG16_ver1_adam.ipynb	: Used Adam optimizer=>This was terminated half way bcos the acc score is bad, and spike time.
CNN_VGG16_version2_SGDoptimizer.ipynb	: Completed all epoch, but bad result. 

I had to stop using this method because my capstone is due in a week time. 
I need to find another solution.

You may view the log scores in XXX_logs.csv 
I will look into this problem when I have the time.
