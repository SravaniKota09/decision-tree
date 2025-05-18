# decision-tree
### Project Description: Decision Tree Classifier for Bill Authentication

This project demonstrates the implementation of a Decision Tree classifier to authenticate banknotes using the "bill_authentication.csv" dataset. The dataset contains features such as variance, skewness, curtosis, and entropy of wavelet-transformed images of banknotes, along with a binary class label indicating authenticity (0 for genuine, 1 for fake).

#### Key Steps:
1. **Data Loading and Exploration**: The dataset is loaded and inspected to understand its structure.
2. **Data Splitting**: The data is split into training and testing sets to evaluate model performance.
3. **Model Training**: A Decision Tree classifier is trained on the training data.
4. **Prediction and Evaluation**: The model's performance is assessed using accuracy, confusion matrix, and classification report.
5. **Visualization**: The decision tree structure is visualized to understand the model's decision-making process.

#### Results:
- The model achieves an accuracy of approximately **94.91%** on the test set.
- Detailed metrics (precision, recall, F1-score) are provided for both classes (genuine and fake).

#### Tools Used:
- Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`.
- Jupyter Notebook for interactive development.

This project is ideal for beginners learning about Decision Trees and binary classification tasks. The code is well-commented and structured for easy understanding. Contributions and feedback are welcome!
