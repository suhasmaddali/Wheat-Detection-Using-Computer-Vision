# 🌾🍚 Wheat Localization With Convolutional Neural Networks (CNNs)

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction
We use __wheat__ everyday in the form of __bread__, __oats__ and other important breakfast and lunch items. It would be really good if the manual process of detecting wheat and their __density__ is replaced by __machine learning__ and __data science__. Since there are many forms of wheat, we must be identifying the right kinds of wheat plants so that they could be processed quickly. This could be done with the __convolutional neural networks (CNNs)__ and it becomes a computer vision problem. 

<img src = "https://github.com/suhasmaddali/Images/blob/main/melissa-askew-y4xZxzN754M-unsplash.jpg" width = 750/>

It is also important to accurately detect the wheat plants and sometimes the wind could blur the images. In addition to this, there could be factors such as __maturity__, __color__, __genotype__, and __head orientation__ that could make detecting and classifying wheat a challenging task. 

## Computer Vision

With the aid of __computer vision__, it is possible to count the total number of wheat heads present in an image. We do this by giving annotated examples of various images and the count of the wheat heads. As we are annotating those images, soon the computer vision model learns from the data and labels and predicts the density of wheat plants from an image. As a result, one could estimate the total density of wheat plants in a particular area. Furthermore, steps can be taken to improve the yield if their density is predicted to be low by the computer vision models and vice-versa.

## 💻 Training with NVIDIA's RTX 2080 graphics card for Computer Vision Tasks 

* __GPU-accelerated deep learning frameworks__ offer flexibility to design and train __deep neural networks__.
* With __cuDNN__ and __Nvidia's graphics drivers__, I was able to train the models really quickly by using __GPU__ cores rather than the __CPU__ cores.
* This led to a significant increase in the __speed of training__ and __developing convolutional neural networks (CNNs)__.  


## 👉 Directions to download the repository and run the notebook 

This is for the Washington Bike Demand Prediction repository. But the same steps could be followed for this repository. 

1. You'll have to download and install Git that could be used for cloning the repositories that are present. The link to download Git is https://git-scm.com/downloads.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(14).png" width = "600"/>
 
2. Once "Git" is downloaded and installed, you'll have to right-click on the location where you would like to download this repository. I would like to store it in "Git Folder" location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(15).png" width = "600" />

3. If you have successfully installed Git, you'll get an option called "Gitbash Here" when you right-click on a particular location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(16).png" width = "600" />


4. Once the Gitbash terminal opens, you'll need to write "Git clone" and then paste the link of the repository.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(18).png" width = "600" />

5. The link of the repository can be found when you click on "Code" (Green button) and then, there would be a html link just below. Therefore, the command to download a particular repository should be "Git clone html" where the html is replaced by the link to this repository. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(17).png" width = "600" />

6. After successfully downloading the repository, there should be a folder with the name of the repository as can be seen below.

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(19).png" width = "600" />

7. Once the repository is downloaded, go to the start button and search for "Anaconda Prompt" if you have anaconda installed. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(20).png" width = "600" />

8. Later, open the jupyter notebook by writing "jupyter notebook" in the Anaconda prompt. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(21).png" width = "600" />

9. Now the following would open with a list of directories. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(22).png" width = "600" />

10. Search for the location where you have downloaded the repository. Be sure to open that folder. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(12).png" width = "600" />

11. You might now run the .ipynb files present in the repository to open the notebook and the python code present in it. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Wheat-Detection-Using-Computer-Vision/blob/main/images/Screenshot%20(13).png" width = "600" />

That's it, you should be able to read the code now. Thanks. 
