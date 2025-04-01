# Indian Medicinal Plant Detection

## Overview

This project uses machine learning to identify Indian medicinal plants. Given an image of a plant, the model predicts the plant's name and provides additional information such as its botanical name, family, uses, and properties. The model is built using Convolutional Neural Networks (CNN) with TensorFlow, and the current version recognizes 40 medicinal plant species.

Currently the model has limitations due to the current dataset and accuracy, it is designed to be improved in the future by adding more plant classes and refining the prediction algorithm for better performance.


## Features

- **Image Upload:** Users can upload an image of a plant, and the model will predict the plant's name.
- **Predictions:** The model provides the predicted class along with the botanical name, plant family, description, and common uses of the plant.
- **Future Enhancements:** Additional plant classes will be added in future updates, and the accuracy of predictions will be improved by expanding the dataset.


### Prerequisites

- Python 3.9 ( Strictly )
- TensorFlow
- OpenCV
- Streamlit
- Numpy


## Installation

To run this project locally, you'll need to have Python installed along with the required libraries. 
Steps:

1. **Clone the repository or download zip**

2. **pip install -r requirements.txt**

3. **Ensure you have ml model saved in project directory**

4. **Run application**  
   ```bash
   streamlit run app.py


## This code deployed here (test here): 
[https://visioneer-megrb6lbcgmz9ipqc86jnv.streamlit.app/](https://visioneer-megrb6lbcgmz9ipqc86jnv.streamlit.app/)


## Dataset Source : 
[https://data.mendeley.com/datasets/748f8jkphb/3](https://data.mendeley.com/datasets/748f8jkphb/3)


## Model 

The model used for plant identification is a deep learning model built using TensorFlow's Keras API. It is trained on a dataset of 40 medicinal plant species and predicts the plant's class based on the uploaded image. The model returns predictions along with a confidence score, and further information about the plant is displayed.

