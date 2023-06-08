# Breast Cancer Prediction System using Flask

![image](https://github.com/Abhaykumar04/Breast_Cancer_Prediction/assets/112232080/aa123556-6e9e-4181-9163-4e07f22aff2e)


This project focuses on developing a web-based breast cancer prediction system using Flask, a popular web framework in Python. The system aims to predict whether a patient is likely to have breast cancer or not. By leveraging machine learning techniques, it provides a valuable tool for early detection and diagnosis.

### Project Overview

The breast cancer prediction system employs a supervised learning approach to classify patients into two categories: malignant (cancerous) or benign (non-cancerous). The system is built using various machine learning algorithms and follows a typical workflow, including data preprocessing, model training, and web application development.

### Key Packages Utilized

The project relies on several key packages to accomplish its objectives:

- Scikit-learn: Scikit-learn, a popular machine learning library, is used for building and evaluating predictive models. It provides a wide range of algorithms for classification, including logistic regression, support vector machines, random forests, and more.
- Pandas: Pandas is employed for data preprocessing and manipulation tasks. It facilitates tasks such as data cleaning, feature selection, and transformation, ensuring the dataset is in a suitable format for machine learning.
- Flask: Flask, a lightweight web framework in Python, is utilized to develop the web application. Flask simplifies the process of creating routes, handling user requests, and rendering responses. It enables the integration of machine learning models into the web interface.
- HTML/CSS: HTML and CSS are used to design the user interface of the web application. HTML is employed for structuring the content, while CSS is utilized for styling and visual enhancements. These technologies ensure an intuitive and visually appealing user experience.

### System Workflow

The breast cancer prediction system follows the following workflow:

1. Data Collection: Relevant breast cancer data is collected, typically consisting of various features such as patient age, tumor size, histology, hormone receptor status, and more.
2. Data Preprocessing: The collected data is preprocessed to handle missing values, remove outliers, and perform feature engineering if necessary. Pandas is used for these tasks.
3. Model Training: Machine learning models, such as logistic regression, support vector machines, or random forests, are trained on the preprocessed data using Scikit-learn. The models learn patterns from historical data to make predictions.
4. Model Evaluation: The trained models are evaluated using suitable evaluation metrics, such as accuracy, precision, recall, or F1-score. This ensures the models' performance is assessed and helps in selecting the most accurate model.
5. Web Application Development: Using Flask, a web application is developed to provide an interface for users to input their data and receive predictions. HTML and CSS are used for designing the user interface, creating an intuitive and visually appealing experience.
6. Deployment: The web application is deployed, allowing users to access it through a browser. Users can input their information, and the system will make predictions based on the trained machine learning model.

### Conclusion

The breast cancer prediction system developed using Flask provides a user-friendly interface for predicting breast cancer likelihood. By leveraging machine learning algorithms, the system empowers healthcare professionals and individuals to make informed decisions and potentially detect breast cancer at an early stage.

Please refer to the code files in this repository for a detailed implementation of the breast cancer prediction system. Feel free to customize and modify the code according to your specific requirements and data.

Remember to provide the necessary data and ensure compliance with ethical considerations while utilizing the system for practical purposes.
