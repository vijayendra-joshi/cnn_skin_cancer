# Melanoma detection using CNN
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
> The data set contains the following diseases:

Actinic keratosis, 
Basal cell carcinoma, 
Dermatofibroma,
Melanoma,
Nevus,
Pigmented benign keratosis,
Seborrheic keratosis,
Squamous cell carcinoma,
Vascular lesion,


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- Evaluate images and alert the dermatologists about the presence of melanoma
- Reduce a lot of manual effort needed in diagnosis.
- 75% of skin cancer deaths


## Technologies Used
- tensorflow 
- keras
- pandas
- matplotlib.pyplot
- Jupyter

## Conclusions
- Model 1 with 3 convolution layers, epoch 20 has training accuracy: 89%, validation accuracy:52%. Has overfitting.
- Model 2 with multiple convolution layers and dropouts, epoch 20 has training accuracy: 43%, validation accuracy:40%. Gap is reduced 
- Model 3 was built with epoch 20, with augmentation. It reduced the gap between training and validation accuracy.
- Model 4 with epoch 30, post handling class imbalance using augmentor increased training and validation dataset accuracy. training accuracy: 95%, validation accuracy:78%. 
