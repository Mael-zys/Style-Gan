# Style-Gan

Our codes contain two parts : StyleGAN and FaceAttribute-FAN.

All the codes are executed on google colab (the environment will be set automatically each time).

The main idea is to firstly generate different images using StyleGAN, 
then obtain the scores of attributes for the images using FAN classifier.

Preparation：

1. Upload the all files on google drive and then unzip all zip files. 

2. Please download the trained models from [Google drive](https://drive.google.com/open?id=1DFd2pvLUEYo2CawaYH_CWVqsAiFtihcz) or [Baidu drive](https://pan.baidu.com/s/1JJ7qqPE2InIqCXKbfjxfSw), and put it into FAN's outputs folder.

To run our code:
1.  run styleGAN.ipynb to generate images of a particular attribute
2.  run FAN_classifier.ipynb to get the scores and plot figures
