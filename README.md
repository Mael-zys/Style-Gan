# Style-Gan

Our codes contain two parts : StyleGAN and FaceAttribute-FAN.

All the codes are executed on google colab (the environment will be set automatically each time).

The main idea is to firstly generate different images using StyleGAN, 
then obtain the scores of attributes for the images using FAN classifier.

Preparation：
Upload the all files on google drive and then unzip all zip files. 

To run our code:
1.  run styleGAN.ipynb to generate images of a particular attribute
2.  run FAN_classifier.ipynb to get the scores and plot figures
