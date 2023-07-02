# Crack Detection Framework

This project framework aims to detect cracks using a binary classification approach. The framework consists of three stages, with the first stage focusing on binary classification. Below, you will find information about the accuracy, confusion matrix, and loss metrics for this stage.

## Stage 1: Binary Classification

In the first stage of the crack detection framework, the goal is to classify images as either cracked or not cracked. The model is trained on a labeled dataset containing images of different surfaces.

### Accuracy

The accuracy metric measures the overall correctness of the binary classification model.

![Logo](https://cdn.discordapp.com/attachments/760172853026226177/1121181452327985252/AccuracyMetuOlentFinal.png)

### Confusion Matrix

The confusion matrix provides detailed information about the model's performance, including true positive (TP), true negative (TN), false positive (FP), and false negative (FN) predictions.

![Logo](https://cdn.discordapp.com/attachments/760172853026226177/1121181453355597997/CmMetuOlentFinal.png)
### Loss

The loss metric indicates how well the model is learning during training. It represents the error between the predicted and actual values.

![Logo](https://cdn.discordapp.com/attachments/760172853026226177/1121181451845636227/LossMetuOlentFinal.png)

## Stage 2: Multi-Class Classification

In the second stage of the crack detection framework, the goal is to classify images into different categories, including roads, solar cells, and tooth cracks. The model is trained on a labeled dataset containing images representing each class.

### Accuracy

The accuracy metric measures the overall correctness of the multi-class classification model.

- Training Accuracy: 95.90%
- Validation Accuracy: 95.83%
- Test Accuracy: 98.69%

### Confusion Matrix

The confusion matrix provides detailed information about the model's performance for each class, including true positives (TP), true negatives (TN), false positives (FP), and false negatives (FN) predictions.

![Logo](https://cdn.discordapp.com/attachments/760172853026226177/1121181454299316274/CMFinalRoadbonessolar.png)

### Loss

The loss metric indicates how well the model is learning during training. It represents the error between the predicted and actual values.

![Logo](https://cdn.discordapp.com/attachments/760172853026226177/1121181453951180850/Loss.png)


## Stage 3: Solar Cells Crack Detection Classification

In the final stage of the crack detection framework, we aim to classify images into different categories representing four types of solar cell cracks: Mirco Crack , Dark Area ,  Oxygen and Cross. The model is trained on a labeled dataset containing images representing each class.

### Loss

The loss metric indicates how well the model is learning during training. It represents the error between the predicted and actual values.

- Train set: 0.0350 
- Val set: 0.0358
- Test set: Average loss: 0.0348

![Loss Image](https://cdn.discordapp.com/attachments/760172853026226177/1121916271915704451/LossPV.png)


The loss chart will provide insights about how well the model is learning and if there are signs of overfitting or underfitting. These insights will ultimately guide further improvements in the model.
