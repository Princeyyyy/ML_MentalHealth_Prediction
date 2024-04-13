# Detection, Prediction, and Analysis of Mental Well-being

Prediction of Mental Wellness for Adults using Machine Learning with a Mental Health Dataset of employees in a technical organization.

## Problem Statement

Mental health issues affect individuals across all age groups, with rising concerns about the lack of awareness and the stigma surrounding mental health. Early detection of mental health vulnerabilities is crucial for timely intervention and support.

## Technologies Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Pickle
- Flask
- HTML
- CSS
- Various machine learning algorithms

## Additional Information

### Flask Web Application (app.py)

The Flask web application serves as the user interface for interacting with the machine learning models. It includes the following routes:

- **/**: Renders the home page (`index.html`).
- **/accuracy**: Renders a page (`accuracy.html`) displaying the accuracy of the machine learning models.
- **/predict**: Accepts POST requests with form data to make predictions using the trained model and renders a page (`predict.html`) with the prediction result.

### Machine Learning Model (ml_project_updated.py)

This Python script contains the code for data preprocessing, model training, and evaluation. It includes the following key steps:

1. Data preprocessing:
   - Handling missing values
   - Encoding categorical variables
   - Data visualization and analysis

2. Model training:
   - Training various machine learning models such as RandomForestClassifier, AdaBoostClassifier, and KNeighborsClassifier.

3. Model evaluation:
   - Calculating accuracy scores for each model

4. Saving the trained model (`model.pkl`) using Pickle for later use in the Flask application.

### Files

- **study_survey.csv**: Dataset containing survey responses related to mental health.
- **model.pkl**: Trained machine learning model saved using Pickle for deployment in the Flask application.

## Conclusion

In this project, machine learning models were employed to predict mental health conditions. Among the models tested, the AdaBoost classifier demonstrated superior performance with an accuracy of 81.746%, outperforming KNN (78.307%) and RandomForest (80.423%) classifiers.

The utilization of machine learning algorithms for mental health prediction holds promise for early detection and intervention, contributing to improved mental well-being and support for individuals in need.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.