# IEEE VGG16 Cats and Dog Classifier
This project is sponsored by UW Madison Student Chapter of IEEE. This project is a seminar code for the IEEE - Intro to Machine Learning event. The goal of this project is to leverage a established machine learning model to classify simple images -- cats and dogs for this event. Through a hands-on experience, this abstract tutorial on machine learning seeks to inspire and improve familarity with machine learning and machine learning concepts.  

This project leverages the architecture of the VGG16 Model. The VGG16 is a 16 layer convultional deep network that was originally trained on ImageNet. For this project, only the architecture will be used and the weights will be trained using Kaggle Cats and Dogs Dataset

## Code Components
- Data Preperation
- Model Setup
- Model Training
- Model Utilization

## Package Requirements
This machine learning project uses the following libraries and modules:
-Keras 2.2.2
-Tensorflow 1.8.0
-Numpy 1.14
-Matplotlib 2.2.2
-itertools

### Recommended Tools and Software
- Anaconda
- Jupyter Notebook


## Current Performance
As of 8/18/2018, and with a data set of roughly 1200 images, the model has an accuracy of 98% and a validation accuracy of 70% after 100 epochs. However, when using the test data set, and as seen in the confusion matrix, Out of 191 tested images, 44 images were classified correctly. The area with the largest missclasification is the contusion category. This indicates few possible problems. First, the data may be diry, or bad. Second, the data may be baised towards contusions. Third, the data set may be to small regarding its test images. Fourth, the model may have been overfitting, even though it is not apparently seen. Overall, these problems can be rectified by simply expanding the data set, perferabely with the goal that every category has roughly the same image count and quality. 

**Review**
- X Epochs
- X Batch Size

## Author
* **Russel Mendes** 
## **Disclaimer**
- The data that was used for this seminar was retrieved from Microsoft.com and is known as the "Kaggle Cats and Dogs Dataset"

## Credits
* This seminar was created by Russel Mendes - https://github.com/Russel-Mendes