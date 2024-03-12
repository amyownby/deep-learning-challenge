# deep-learning-challenge

## written report

For this assignment, I looked at a csv dataset containing thousands of organizations that have received funding from a nonprofit foundation called Alphabet Soup over the years. Some potential objectives for the analysis could be: predicting whether applicants will be successful or not with the funding from Alphabet Soup using predictive modeling, providing insights to help Alphabet Soup make informed decisions about funding applicants, and fine tuning hyperparameters of the models to achieve better results, for example.

## overview
The objective of this analysis is to create a resource for the Alphabet Soup Foundation, a non-profit entity, aiding in the identification of funding candidates likely to succeed in their endeavors. Utilizing advanced deep learning methodologies, our goal is to construct a predictive framework capable of categorizing applicants according to a range of attributes. This will empower the foundation to make well-informed decisions regarding the allocation of resources.

![Screenshot 2024-03-11 205241](https://github.com/amyownby/deep-learning-challenge/assets/145077707/222435ff-867c-45e1-b7fe-43262a68e2ac)

## data reprocessing
Target Variable(s): The focus variable for our model is the outcome of the applicants' ventures, which could be expressed as a binary result, denoting either "successful" or "unsuccessful."
Feature Variable(s): Attributes considered for our model encompass a diverse range of applicant characteristics, comprising project descriptions, past performance, financial data, team composition, and more.
Variable(s) to be Removed: Non-essential variables, including unique identifiers and irrelevant metadata, should be excluded from the input data to enhance the model's efficiency.

## compiling, training, and evaluating the model
1. We opted for a multi-layered architecture with numerous hidden neurons to capture intricate data relationships. Activation functions such as ReLU (Rectified Linear Unit) are commonly applied in hidden layers for their capacity to introduce non-linearity, while the choice between sigmoid or softmax functions for output layers depends on the classification task's specifics.
2. Attaining the desired model performance hinges on several factors, including data quality, feature selection, model architecture, and hyperparameter adjustments. Through iterative training and assessment, our objective is to enhance the model's performance metrics, encompassing accuracy, precision, recall, and F1-score.
3. In our pursuit of improved model performance, we explored various architectures, activation functions, learning rates, regularization techniques, and optimization algorithms. Furthermore, we applied methodologies such as feature engineering, dimensionality reduction, and data augmentation to bolster the model's generalization and resilience.

## summary
In conclusion, the deep learning model developed for Alphabet Soup Foundation demonstrates promising outcomes in predicting the success of applicants' ventures. However, to mitigate potential constraints and further enhance performance, we suggest exploring alternative machine learning models such as gradient boosting machines (GBM), random forests, or support vector machines (SVM). These models offer benefits in managing non-linear relationships, conducting feature importance analysis, and resilience to overfitting, potentially providing valuable insights to complement the predictive capabilities of the deep learning model. Through the integration of multiple models or ensemble techniques, Alphabet Soup Foundation can establish a comprehensive applicant selection tool that harnesses the strengths of each approach, thereby enhancing decision-making and maximizing the impact of their funding endeavors.
