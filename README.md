Question 1: Data Preprocessing (Medium)

    a. Load the MNIST handwritten digit dataset and perform the following pre-processing steps:
    
    b. Normalize the pixel values of the images.
    
    c. Apply one-hot encoding to the target labels.
    
    d. Split the data into training, validation, and test sets.
    
    e. Dataset: https://github.com/iamavieira/handwritten-digits-mnist
    
    
Question 2: Classification (Hard)

    a. Build a logistic regression model to classify handwritten digits from the MNIST dataset.
    
    b. Evaluate the model performance using accuracy, precision, recall, and F1 score.
    
    c. Fine-tune the model hyperparameters using grid search CV to improve performance.
    
    d. Visualize the decision boundary of the model.

Question 3: Clustering (Medium)

    a. Apply K-means clustering to group customers based on their purchase history
    and demographic information.
    
    b. Determine the optimal number of clusters using the elbow method.
    
    c. Analyze the characteristics of each cluster to identify customer segments.
    
    d. Visualize the clusters using scatter plots and dimensionality reduction
    techniques.
    
    e. Dataset: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

Question 4: Feature Selection:

The Iris dataset consists of 150 samples with 4 features each: sepal length, sepal width, petal
length, and petal width. Each sample belongs to one of three classes: setosa, versicolor, or
virginica.

    a. Load the Iris dataset and split it into features (X) and target labels (y).
    
    b. Perform exploratory data analysis (EDA) to gain insights into the dataset.
    
    c. Implement feature selection techniques:
    
        a. Univariate Feature Selection
        
        b. Feature Importance using Random Forest
        
        c. Recursive Feature Elimination (RFE) using Support Vector Machine (SVM)
    
    d. Evaluate the performance of the selected features using a classification model (e.g., SVM
    or Logistic Regression).
    
    e. Compare the model performance before and after feature selection
