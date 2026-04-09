# Pet Classifier: Dog vs Cat
Final project for the Building AI course

## Summary

This project uses artificial intelligence to classify whether an animal is a dog or a cat based on physical features such as height, weight, and length. The model uses a neural network to make predictions and assist in animal identification.

## Background

This project solves real-world problems related to animal identification:

* Animal shelters may struggle with quick and accurate classification of pets
* Pet owners may need help identifying animals based on physical traits
* Manual classification can be time-consuming and prone to human error

My personal motivation is to explore how AI can be used in practical, everyday situations such as animal care and management. This topic is interesting because it shows how simple data can be used to make useful predictions.

## How is it used?

The system works by taking measurements of an animal and predicting whether it is a dog or a cat.

Steps:
1. The user inputs the animal's height, weight, and length
2. The AI model processes the input
3. The system outputs the probability of the animal being a dog or a cat

Users:
* Animal shelter workers
* Veterinarians
* Pet owners

The solution can be used on a computer or mobile device for quick and easy predictions.

![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

## Data sources and AI methods

The data used in this project is a simple dataset of animal measurements:

* Height
* Weight
* Length
* Label (0 = cat, 1 = dog)

The dataset can be manually created or collected from animal shelters.

AI methods used:
* Neural networks
* Logistic regression (as a baseline model)
* Sigmoid activation function for binary classification
  
## Challenges

This project has some limitations:

* Small datasets may reduce accuracy
* Some animals may have similar features, causing misclassification
* It does not handle mixed breeds or unusual cases well

Ethical considerations:
* The system should not replace expert judgement
* Predictions should be used as assistance, not final decisions

## What next?

This project can be improved in several ways:

* Add more features such as fur color, breed, and age
* Use a larger and more realistic dataset
* Expand to classify more types of animals
* Build a mobile or web application for easier access

To move forward, more data, better models, and software development skills will be needed.

## Acknowledgments

* Building AI course by University of Helsinki and Reaktor
* Inspiration from course materials and exercises
* Image: Sleeping Cat on Her Back by Umberto Salvagnin / CC BY 2.0
