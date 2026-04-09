# Pet Classifier: Dog vs Cat
Building AI Course Project
## Summary

This project predicts whether an animal is a dog or a cat based on physical attributes such as height, weight, and length. A neural network model is used to classify animals efficiently for shelters and pet owners.

## Background

The project aims to solve real-world issues in animal care and management:

* Manual classification of pets in shelters is time-consuming and prone to errors.
* Pet owners may want quick identification of their pet species.
* Personal motivation: Interested in AI applications for animal welfare and practical classification tasks.

## How is it used?

The solution works as follows:

1. Collect measurements of the animal: height, weight, length.
2. Input these values into the classifier.
3. The neural network outputs the probability of the animal being a dog or a cat.
4. The user interprets the results for records or recommendations.

Users include animal shelter staff, veterinarians, or pet owners. The tool can be deployed on a desktop, web app, or mobile interface for quick access.

![Pet Classifier Diagram](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

## Data sources and AI methods

* Data: Open datasets of dog and cat measurements; additional simulated data for training purposes.
* AI methods: 
  * Neural network with input nodes for height, weight, and length.
  * Hidden layer uses sigmoid or ReLU activation functions.
  * Output layer uses sigmoid for binary classification (dog vs cat).
* Tools: Python, NumPy, Pandas, TensorFlow/Keras for model training and evaluation.

Example dataset link: [Open Pet Dataset](https://example.com/dataset)

```python
# Sample code to predict using the trained model
import tensorflow as tf
import numpy as np

# Example input: height, weight, length
animal_features = np.array([[40, 10, 50]])

# Load trained model (assume saved as pet_model.h5)
model = tf.keras.models.load_model('pet_model.h5')

# Predict probability
prob = model.predict(animal_features)
print(f"Probability of being a dog: {prob[0][0]:.2f}")
