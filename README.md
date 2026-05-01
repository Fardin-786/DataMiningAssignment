📊 Data Mining Assignments (Machine Learning)

This repository presents a collection of three practical machine learning assignments developed using Python and the powerful scikit-learn library. The objective of these assignments is to demonstrate the application of fundamental classification algorithms on well-known datasets, along with proper data preprocessing, model training, and performance evaluation.

Machine learning plays a crucial role in modern data analysis, enabling systems to learn patterns from data and make intelligent decisions. This repository focuses on supervised learning techniques, where models are trained on labeled datasets and then used to predict outcomes on unseen data.


🎯 Objectives

* To understand the implementation of core classification algorithms
* To apply preprocessing techniques such as normalization and data splitting
* To evaluate model performance using accuracy metrics
* To gain hands-on experience with real-world datasets
* To compare different machine learning approaches


📌 Assignment 1: Digit Recognition using Logistic Regression
Dataset: MNIST (from OpenML)
Algorithm: Logistic Regression

📖 Description
This assignment focuses on recognizing handwritten digits (0–9) using Logistic Regression, a widely used linear classification algorithm. The MNIST dataset consists of 70,000 grayscale images of handwritten digits, each represented as a 28×28 pixel grid.
Each image is flattened into a vector of 784 features and normalized to improve model performance. The dataset is then divided into training and testing subsets. The Logistic Regression model learns the relationship between pixel intensities and digit labels, and it predicts the class of unseen images.
Despite being a simple linear model, Logistic Regression performs remarkably well on this dataset due to its ability to handle multi-class classification using techniques like one-vs-rest.

⚙️ Key Steps

* Data loading from OpenML
* Feature normalization (scaling pixel values between 0 and 1)
* Train-test split
* Model training using Logistic Regression
* Prediction on test data
* Accuracy evaluation

📊 Outcome

The model achieves an accuracy of approximately **95–100%**, demonstrating the effectiveness of Logistic Regression for image classification tasks.

---

📌 Assignment 2: Digit Recognition using Naive Bayes

Dataset: MNIST (from OpenML)
Algorithm: Gaussian Naive Bayes

📖 Description

This assignment applies the Gaussian Naive Bayes algorithm to classify handwritten digits. Naive Bayes is a probabilistic classifier based on Bayes’ Theorem, which assumes that all features are conditionally independent given the class label.
In this implementation, each pixel value is treated as an independent feature following a Gaussian (normal) distribution. The model calculates the probability of each class given the input features and selects the class with the highest probability.
Although the independence assumption is often unrealistic for image data, Naive Bayes remains computationally efficient and performs reasonably well.

⚙️ Key Steps

* Data preprocessing and normalization
* Model training using Gaussian Naive Bayes
* Probability-based classification
* Model evaluation using accuracy

📊 Outcome

The model achieves an accuracy of approximately **80–85%**, which is lower than Logistic Regression but still demonstrates the usefulness of probabilistic methods.



📌 Assignment 3: Iris Flower Classification using K-Nearest Neighbors (KNN)

Dataset: Iris Dataset
Algorithm: K-Nearest Neighbors (KNN)

📖 Description

The dataset includes four features: sepal length, sepal width, petal length, and petal width. The KNN algorithm classifies a data point based on the majority class among its nearest neighbors in the feature space.
KNN is a non-parametric, instance-based learning algorithm that does not explicitly train a model but instead stores the training data and makes predictions based on similarity.

⚙️ Key Steps

* Load dataset from scikit-learn
* Feature selection and preprocessing
* Choosing an appropriate value of K
* Distance calculation (Euclidean distance)
* Classification based on nearest neighbors

📊 Outcome

The model achieves an accuracy of approximately **95–100%**, showing excellent performance on this simple and well-structured dataset.

📌 Assignment 4. Cancer Data Classification
Dataset: Breast Cancer Dataset (from scikit-learn)
Algorithm: Logistic Regression / Classification Model
Description: This program classifies tumors as malignant or benign using machine learning techniques based on various medical features.

What has been done:

Loaded the breast cancer dataset
Preprocessed and normalized the data
Split the dataset into training and testing sets
Trained the model using classification algorithm
Evaluated performance using accuracy score


⚙️ Technologies Used

Programming Language: Python
Libraries:

  * NumPy – for numerical computations
  * Matplotlib – for visualization
  * scikit-learn – for machine learning algorithms

▶️ How to Run the Project

1. Install the required libraries:

   ```bash
   pip install numpy matplotlib scikit-learn
   ```

2. Clone the repository:

   ```bash
   git clone <repository-link>
   ```

3. Navigate to the project folder:

   ```bash
   cd project-folder
   ```

4. Run any assignment file:

   ```bash
   python main.py
   ```


📊 Performance Summary

| Algorithm           | Dataset | Accuracy |
| ------------------- | ------- | -------- |
| Logistic Regression | MNIST   | 95–100%   |
| Naive Bayes         | MNIST   | 85–90%   |
| KNN                 | Iris    | 95–100%  |


📚 Dataset Sources

* MNIST dataset from OpenML
* Iris dataset from scikit-learn



🚀 Future Enhancements

* Implementation of additional algorithms such as Decision Trees and Support Vector Machines
* Hyperparameter tuning for improved performance
* Visualization of results using confusion matrices and graphs
* Deployment as a web application using Streamlit or Flask
* Integration with deep learning models for higher accuracy



🎓 Learning Outcomes

Through this project, the following concepts are understood:

* Supervised learning techniques
* Classification algorithms and their differences
* Data preprocessing and normalization
* Model evaluation and accuracy metrics
* Practical implementation of machine learning using Python



👨‍💻 Author

Fardin Ahmed
