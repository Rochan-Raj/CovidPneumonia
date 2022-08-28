# Covid_Pneumonia_Detector


## Description:

Considering the global pandemic COVID-19, how AI and ML could help us in detecting lung disease through the given dataset of chest X-RAY images . 
After doing some sort of research here I have come across my new deep learning project which detects Covid-Pneumonia using VGG16 Transfer Learning which is a type of CNN (Convolutional Neural Networks) image classification algorithm.

## Now, the question arises, what is Transfer Learning?

Transfer learning is the reuse of a pre-trained model on a new problem. This is very useful since most real-world problems typically do not have millions of labelled data points to train such complex models. In transfer learning, the knowledge of an already trained ML model is applied to a different but related problem. With transfer learning, we try to exploit what has been learned in one task to improve generalization in another. We transfer the weights that a network has learned at “task A” to a new “task B.”

So, in the end, how we will come to know whether the uploaded image was normal or pneumonia infected?
Well, after adding the path of the X-RAY image and running the trained model if the output results in the form of [0,1] format then the added image was pneumonia infected. Rest all the cases the result is normal. (You can refer to the related images.)

## List of modules used:

•	tensorflow

•	keras

•	VGG16

•	numpy

•	glob

•	os

•	matplotlib

## Dataset:

•	kaggle

## Related Pics
![image](https://user-images.githubusercontent.com/85439772/187086397-9fd13abb-a549-4d16-a718-e445a4aa5955.png)

![image](https://user-images.githubusercontent.com/85439772/187086402-bd7226a0-5727-4d03-9f5a-ef479de65b67.png)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


