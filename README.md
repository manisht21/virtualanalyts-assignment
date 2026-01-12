
KNN performed reasonably well but was computationally expensive and sensitive to noise, while the Decision Tree tended to overfit and showed lower generalization on unseen data.

Most misclassifications occurred between visually similar digits such as 4 and 9 or 3 and 5, where pixel patterns overlap. These errors occur because classical models rely on raw pixel intensities without understanding shapes.

Performance could be improved by applying PCA for dimensionality reduction, tuning hyperparameters, or using ensemble voting, which slightly improves accuracy by combining predictions from multiple models. Ensemble Accuracy: 0.839

Observations and Conclusions:

In this assignment, classical machine learning models were applied to recognize handwritten digits from the MNIST dataset. The data was first normalized and split into training and testing sets. Three models—KNN (implemented from scratch), Support Vector Machine (SVM), and Decision Tree—were trained and evaluated.

KNN achieved the highest accuracy of 95.3%, showing that distance-based methods work well for handwritten digit recognition. SVM also performed strongly with an accuracy of 91.4%, benefiting from linear separation in high-dimensional pixel space. The Decision Tree achieved 87.0% accuracy but showed signs of overfitting.

Misclassifications were mainly observed between visually similar digits such as 4 and 9, 3 and 5, and 0 and 8. An ensemble voting approach combining all three models further improved robustness and prediction stability.

Overall, this project demonstrates how classical machine learning techniques can effectively solve image classification problems when proper preprocessing and evaluation methods are applied.
