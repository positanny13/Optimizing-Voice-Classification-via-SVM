# Optimizing-Voice-Classification-via-SVM
SVMs, a powerful machine learning technique, emerged as the perfect solution. SVMs are widely used for binary classification tasks, such as determining spam emails, identifying fraudulent transactions, or, in our case, classifying voices as male or female. 
The essence of SVMs lies in finding a hyperplane that best separates two classes while maximizing the margin between them. This creates a robust model that can make accurate predictions even on complex data like voice features.

This project described is focused on solving a specific challenge faced by Motion Studios, Europe's largest production house. The project's primary goal is to efficiently classify voice clips as either male or female, a crucial step in the selection process for their reality TV show called "The Star RJ." Here's what the project does:

Data Collection: The project begins by collecting voice clips submitted by participants for "The Star RJ" TV show. These clips are used as the dataset for the project.

Data Exploration: The team explores the dataset, which includes various features describing each voice clip, such as mean frequency, skewness, and kurtosis. Understanding the data is essential before building a machine learning model.

Data Preprocessing: The dataset is cleaned and prepared for analysis. In this step, they ensure that there are no missing values and perform label encoding to represent the gender of the voice clips (male or female). Standardization of features is done to make the data more suitable for modeling.

Building the Support Vector Machine (SVM) Model: The core of the project is the creation of an SVM model. SVM is a powerful machine learning technique known for its effectiveness in binary classification tasks. In this case, it's used to classify voice clips as either male or female.

Training and Evaluation: The SVM model is trained on a portion of the dataset and then evaluated on a separate test dataset to assess its performance. Initially, the model achieves an accuracy score of around 97%.

Fine-Tuning with Grid Search: To further improve the model's performance, GridSearchCV is employed. This technique systematically searches for the best combination of hyperparameters for the SVM model, resulting in a slight accuracy improvement to approximately 97.5%.

Results: The final SVM model successfully classifies voice clips with high accuracy, making the first level of filtration for "The Star RJ" quicker and more efficient. The project ensures that the best talent, whether male or female, stands out during the selection process for the reality TV show.

In summary, the project leverages machine learning, specifically SVM, to automate and enhance the process of classifying voice clips, a critical task for Motion Studios in the context of their reality TV show. It ultimately helps the production house identify top talents for "The Star RJ" with greater precision and efficiency.









