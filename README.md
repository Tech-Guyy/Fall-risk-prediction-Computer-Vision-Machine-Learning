# Developing Machine Learning Models for Fall Risk Prediction with Openpose: Utilizing video recordings of gaits

This project focuses on developing and evaluating machine learning models for accurately
classifying individuals into high and low fall risk categories based on video recordings of gaits.
Leveraging OpenPose as a computer vision technique for feature extraction, the study aims to
enhance fall prediction strategies in healthcare settings. The project encompasses several key
objectives: model development, evaluation of various machine learning techniques,
identification of optimal classifiers, and contributing to effective fall prediction strategies.
Support Vector Machine (SVM), K-Nearest Neighbours (KNN), Random Forest (RF),
Decision Tree (DT), and Multi-Layer Perceptron (MLP) were the five machine learning
classifiers used by the author. Among these, the Random Forest classifier exhibited superior
performance, achieving a mean cross-validation accuracy of 93%, an accuracy of 93% on the
test set, and an F1 score of 0.93, along with high sensitivity and specificity values of around
93.50% and 92.50%, respectively. The study exhibited a harmonious integration of heightened
sensitivity and specificity, rendering it well-suited for utilization in medical contexts.
The study also highlights the significance of feature selection. Notably, the velocity of key
points emerged as the most influential feature, outperforming other features such as distance,
angle, mean, and standard deviation of key points. This underscores the importance of a
meticulous feature selection process in building robust fall risk prediction models.
Comparing this approach with existing literature, the project outperforms deep learning
techniques that rely on wearable sensors and traditional fall risk prediction which include the
use of clinical exams, questionnaires, and physical evaluations, achieving superior accuracy,
sensitivity, and specificity. This suggests that the approach, utilizing OpenPose and traditional
machine learning models, offers a compelling alternative for fall risk prediction.
Furthermore, the findings have broad societal implications, including improved fall risk
prediction and personalized healthcare interventions, potentially reducing healthcare costs and
enhancing the quality of life for elderly individuals. The work contributes to the intersection of
technology and healthcare, offering innovative solutions for fall risk prediction. It underscores
the importance of feature selection, model evaluation, and the integration of advanced
technologies in addressing critical health challenges.
