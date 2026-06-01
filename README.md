#Author Shivam Bhardwaj
#Customer Churn 

Project Overview : 

Customer churn is a critical problem for subscription-based businesses. This project uses a neural network to analyze customer behavior and predict churn probability.

The pipeline includes:

. Data preprocessing
. Feature scaling
. PyTorch neural network training
. Model evaluation
. Prediction system


Tech Stack:
Python 
PyTorch 
NumPy
Pandas
Scikit-learn


A fully connected neural network (MLP):

Input Layer: Customer features
Hidden Layers: ReLU activation + Dropout (if used)
Output Layer: Sigmoid activation (binary classification)


Workflow:
Load dataset
Clean and preprocess data
Normalize features
Train neural network using PyTorch
Evaluate performance
Save trained model
Make predictions on new data

Performance
Training Accuracy: ~99%
Loss function: Binary Cross Entropy
Optimizer: Adam

Note: Training accuracy is can be high due to strong fitting on training data or data may be so easy. Real-world generalization depends on validation/testing performance.



## this is my loss graph  after some iteration it becommes constant after a while 
## 📊 Model Output



### 🔥 Prediction Output Visualization

<img src="https://raw.githubusercontent.com/shivambhardwaj-alt/CustomerChurnTorch/main/output.png" width="600"/>


