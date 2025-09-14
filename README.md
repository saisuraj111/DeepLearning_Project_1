## Deep Learning Project: Age Estimator using CNN Classification and Regression Techniques, Involving predictions using Auto encoders, Resnet-50, and Predictions using Deep face

This report details the implementation of a deep learning pipeline for age estimation and
gender bias analysis using the Kaggle facial age dataset
(https://www.kaggle.com/datasets/frabbisw/facial-age), as per the Deep Learning Assignment
2025 requirements. The project is divided into three parts: age estimation with model
variations, autoencoder and transfer learning, and gender bias evaluation. And one Demo
notebook

Part 1: Simple Age Estimator
Part 1 constructs convolutional neural networks (CNNs) for age regression (age prediction as
a continuous value) and classification (age category prediction), experimenting with CNN
kernel differences, network architecture differences, processing the data, and handcrafted
design. The Performance is tested later on training, validation, and test sets, and the top
models are saved after this.

So the demo cosists of the models predicting the accuracy of the one of the best models selected
from the classification cnn models and the regression models

Part 2: Using Backbone Models and Fine Tuning
Part 2 focuses on training of an Autoencoder for unsupervised learning, and then applying
Transfer Learning for age classification and fine-tuning and reuse of the Backbone model for
the enhanced performance. So, we split the non-test data into Block 1 and Block 2 and
continue to train the models accordingly. We will see them in detail in the coming sections.

Similarly here we focus on the models related to Auto encoder, Transfer learning and the 
backbone model re-use (using Residual net 50 or Res-net 50). and then compare the accuracy 
of these models to the best classification model accuracy from the part 1

Part 3: Bias in Data – Gender Bias Analysis Report
Introduction:
The objective of this section is to ascertain whether the inclusion of gender
information boosts the predictive accuracy and whether the mitigation of gender
bias enhances model fairness and generalization. By using the Deep face library to predict
the gender and comparing the biased and balanced models. We use the same dataset splits
as used in the part 1 ensuring a robust framework for comparing model performance with and
without gender bias considerations

Every part has it sample set of predictions on how the model behaves . i.e the true predictions 
vs the Actual predictions.

## License: This project was developed and is intended for academic purposes only. You may view, reference, or adapt the code with proper citation, but commercial use is not permitted.
