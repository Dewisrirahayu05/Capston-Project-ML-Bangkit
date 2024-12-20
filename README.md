# Machine Learning Model

So in this project, we developed a machine learning model that is able to classify brain tumor types based on MRI images. This model uses a Convolutional Neural Network (CNN) architecture that is specifically designed for classification tasks. This model has four convolutional layers equipped with BatchNormalization and MaxPooling. This model is trained using a dataset that has been preprocessed through augmentation and normalization, so that it can produce accurate predictions for brain tumor types. We also trained our model with 30 epochs and after that we obtained the following results:

![image](https://github.com/user-attachments/assets/e3eb1c2b-0ea1-4610-b1fb-2974bd117b68)

![image](https://github.com/user-attachments/assets/43ee3ddf-695b-48c2-8264-abe13ac8cf86)

# Model Evaluation on Testing Data
To evaluate the performance of the model in classifying brain tumor types, we used the Confusion Matrix and Classification Report.

## Here are the results:
![image](https://github.com/user-attachments/assets/525991b0-ac51-4ad2-bb65-b4cb1e8cdf00)

Classification Report:
| Class       | Precision | Recall | F1-Score | Support |
|-------------|-----------|--------|----------|---------|
| Glioma      | 0.99      | 0.92   | 0.96     | 163     |
| Meningioma  | 0.88      | 0.96   | 0.92     | 165     |
| Notumor     | 0.97      | 1.00   | 0.98     | 201     |
| Pituitary   | 0.99      | 0.95   | 0.97     | 176     |
| **Accuracy**|           |        | **0.96** | 705     |
| Macro Avg   | 0.96      | 0.96   | 0.96     | 705     |
| Weighted Avg| 0.96      | 0.96   | 0.96     | 705     |

