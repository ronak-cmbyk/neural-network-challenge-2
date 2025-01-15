## neural-network-challenge-2

* This project implements a multi-layer model with multiple branches through Tensorflow's Keras Sequential model to analyze rate of attrition across departments within an organization.

* Data was collected from a dataset that was scaled using StandardScaler(), encoded using OneHotEncoder(), and processed to create training and testing datasets for the model.

* The model was created, compiled, and trained by creating a 4-layer model with added branches for 'Department' and 'Attrition', respectively, based on the different types of classification. Binary classification occurs for the 'Attrition' branch and multi-class (3 classes) classification occurs for the 'Department'.

* The model was evaluated to determine accuracy and model loss.

* The model was then used to make predictions from training data to determine performance of the model, with an accuracy of .50 for Department predictions, and an accuracy of .82 for Attrition predictions.
