# ML--Plant-Disease-Detection
An image classification deep learning model
![download](https://github.com/iurwpoietknckvjndfsm-gndvkd/ML--Plant-Disease-Detection/assets/103903785/b3158200-2ccd-4e69-a197-5e2c0e5e79a8)

## Requirments
[Requirments](https://github.com/iurwpoietknckvjndfsm-gndvkd/ML--Plant-Disease-Detection/blob/main/Requirments.txt)

## Data
**Data Source**
[link](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

**Our Data**
[Data](https://github.com/iurwpoietknckvjndfsm-gndvkd/ML--Plant-Disease-Detection/blob/main/Data.zip)

**Data Description**
* **Input**: Image
* **Output**: Class
    * Apple___Apple_scab
    * Apple___Black_rot
    * Apple___Cedar_apple_rust
    * Apple___healthy
    * Corn_(maize)___Cercospora_leaf_spot Gray_leaf_spot
    * Corn_(maize)___Common_rust_
    * Corn_(maize)___Northern_Leaf_Blight
    * Corn_(maize)___healthy
    * Grape___Black_rot
    * Grape___Esca_(Black_Measles)
    * Grape___Leaf_blight_(Isariopsis_Leaf_Spot)
    * Grape___healthy
    * Potato___Early_blight
    * Potato___Late_blight
    * Potato___healthy
    * Tomato___Bacterial_spot
    * Tomato___Early_blight
    * Tomato___Late_blight
    * Tomato___Leaf_Mold
    * Tomato___Septoria_leaf_spot
    * Tomato___Spider_mites Two-spotted_spider_mite
    * Tomato___Target_Spot
    * Tomato___Tomato_Yellow_Leaf_Curl_Virus
    * Tomato___Tomato_mosaic_virus
    * Tomato___healthy

## Target
High Accuracy

## Resource/Situational Constraints
* limited resources

## Process followed
* Use free GPU supplied by google colab or kaggle.
* Use a small dataset with 25 classes related to only five types of plants.

## ML Code
1. Splitting Data:
  Take only five plants to work with. I've splitted train folder into train and val sets with val ratio 0.2 after shuffeling. <br/>
  [Code](https://github.com/iurwpoietknckvjndfsm-gndvkd/ML--Plant-Disease-Detection/blob/main/Splitting_Data.ipynb)
