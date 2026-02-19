# ml-internship
Tasks from my internship as a ML Engineer at Prodigy Infotech 

## Task 1: House Price Prediction (Linear Regression)

Objective:  
Predict house prices based on square footage, number of bedrooms, and bathrooms.

Dataset:  
Housing dataset containing features such as `sqft_living`, `bedrooms`, `bathrooms`, and `price`.

Approach:
- Data preprocessing using pandas  
- Train-test split  
- Linear Regression model using scikit-learn  

Evaluation Metrics: 
- Mean Squared Error (MSE)  
- R² Score  

Result:
The model successfully predicts house prices with reasonable accuracy, demonstrating effective use of linear regression for continuous value prediction.


## Task 2: Customer Segmentation using K-Means

Objective:  
Group customers based on their annual income and spending behavior.

Dataset: 
Mall Customers dataset containing demographic and purchasing information.

Approach:
- Feature selection (Annual Income, Spending Score)  
- Data scaling using StandardScaler  
- Optimal cluster selection using Elbow Method  
- K-Means clustering  

Result:
Customers were successfully segmented into distinct groups, enabling targeted marketing strategies.

## Task 3: Cats vs Dogs Image Classification

Objective:
Classify images of cats and dogs using a Support Vector Machine (SVM).

Dataset:  
Image dataset organized into separate folders for cats and dogs.

Approach:  
- Image resizing and flattening  
- Label assignment based on folder structure  
- SVM classification with linear kernel  

Result:  
The model successfully classifies cats and dogs with reasonable accuracy.

## Task 4: Hand Gesture Recognition

Objective: 
Recognize and classify different hand gestures from image data.

Dataset:  
Leap Motion Hand Gesture Recognition dataset.

Approach:  
- Image preprocessing using ImageDataGenerator  
- Convolutional Neural Network (CNN)  
- Multi-class gesture classification  

Result:  
The model successfully learns to classify multiple hand gestures with good accuracy.
