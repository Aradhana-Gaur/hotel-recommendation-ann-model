\# Hotel Recommendation System using ANN



\## Overview

This project implements an Artificial Neural Network (ANN) model for hotel recommendation prediction using Deep Learning techniques.



The model analyzes hotel-related features such as:

\- Hotel type

\- Location

\- Budget

\- Ratings

\- Amenities

\- User preferences



and predicts hotel recommendations.



\---



\## Technologies Used

\- Python

\- Pandas

\- NumPy

\- TensorFlow

\- Keras

\- Scikit-learn

\- Jupyter Notebook



\---



\## Machine Learning Workflow



\### 1. Data Preprocessing

\- Handling categorical and numerical data

\- Feature encoding

\- Train-test split

\- Feature scaling



\### 2. ANN Model Building

The ANN model contains:

\- Input Layer

\- Hidden Dense Layers

\- ReLU activation

\- Sigmoid output layer



\### 3. Model Training

\- Adam optimizer

\- Binary crossentropy loss

\- Accuracy metric



\### 4. Model Evaluation

\- Predictions

\- Confusion Matrix

\- Accuracy analysis



\---



\## ANN Architecture



```python

model = Sequential()



model.add(Dense(units=6, activation='relu'))

model.add(Dense(units=6, activation='relu'))

model.add(Dense(units=1, activation='sigmoid'))

```



\---



\## Project Structure



```bash

hotel-recommendation-ann-model

│

├── dataset/

├── notebook/

├── screenshots/

├── requirements.txt

└── README.md

```



\---



\## Future Improvements

\- Deploy using Streamlit

\- Add recommendation dashboard

\- Improve dataset quality

\- Add NLP review analysis



\---



\## Author

Aradhana Gaur

