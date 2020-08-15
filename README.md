# Detecting COVID-19 with Chest X Ray using PyTorch

#### Objective:

Create Image Classification Model, to predict Chest X_ray scans, that belonged to one of three classes of Chest X rays: Normal, Viral Pneumonia, COVID-19, with a reasonably high accuracy.

#### Dataset:
[COVID-19 Radiography Dataset](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) on Kaggle

#### Technologies used:
Deep Learning, PyTorch

#### Model Creation:
Used ResNet18 pre trained neural network on ImageNet dataset.

#### Training Model:
Trained model, until got accuracy > 95% on training datset, and evaluate on validation dataset-

![alt text](https://github.com/rickhagwal/Covid19_Image_classification/blob/master/images/trained_model_imgs.PNG)


#### Accuracy and Results:

Got accuracy of 97.78% on validation dataset.

Final Results in one batch, on validation dataset is shown below-

![alt text](https://github.com/rickhagwal/Covid19_Image_classification/blob/master/images/final_res.PNG)

