# Classification of exotic fruits

TropicTaste Inc., a leader in the distribution of exotic fruits, aims to improve efficiency and accuracy in the fruit grading process. The goal is to develop a machine learning model that can predict the type of fruit based on numerical characteristics.

The current process of classifying exotic fruits is manual and error-prone, inefficient and resource-intensive. The need for an automated and accurate system is crucial to optimize business operations and maintain high quality standards.

By implementing an automated classification model, TropicTaste Inc. will:

* **Improve operational efficiency:** automating classification will reduce the time and resources required, increasing productivity.
* **Reduce human errors:** a machine learning model will minimize classification errors, ensuring greater accuracy.
* **Optimize inventory:** accurate classification will allow better inventory management, ensuring optimal storage conditions for each type of fruit.
* **Increase customer satisfaction:** a correct identification and classification of fruits will help maintain high quality standards, improving customer satisfaction.

**Project details:**

* **Dataset:** use of a dataset containing various numerical characteristics of different exotic fruits.
* **Algorithm:** implementation of the K-Nearest Neighbors (KNN) algorithm for classification.
* **Output:** the model must correctly predict the type of fruit based on the data provided.

**Project requirements:**

1. **Preparation of the dataset:**
    * Loading and pre-processing of exotic fruit data.
    * Management of missing values, normalization and scaling of data.
2. **Implementation of the KNN model:**
    * Development and training of the KNN model.
    * Parameter optimization to improve predictive accuracy.
3. **Evaluation of performance:**
    * Use of cross-validation techniques to assess the generalizability of the model.
    * Calculation of performance metrics, such as accuracy and classification error.
4. **Display of results:**
    * Create charts to view and compare model performance.
    * Analysis and interpretation of results to identify areas for improvement.

## Variables of the dataset
The dataset can be downloaded from here: https://proai-datasets.s3.eu-west-3.amazonaws.com/fruits.csv.

It contains the following variables:

1. **Frutto:** the type of fruit. This is the target variable (target) that we want to predict.
2. **Peso (g):** the weight of the fruit in grams. Continuous variable.
3. **Diametro medio (mm):** the average diameter of the fruit in millimeters. Continuous variable.
4. **Lunghezza media (mm):** the average length of the fruit in millimetres. Continuous variable.
5. **Durezza buccia (1-10):** the peel hardness of the fruit on a scale from 1 to 10. Continuously variable.
6. **Dolcezza (1-10):** the sweetness of the fruit on a scale from 1 to 10. Continuous variable.
7. **Acidità (1-10):** the acidity of the fruit on a scale from 1 to 10. Continuously variable.
