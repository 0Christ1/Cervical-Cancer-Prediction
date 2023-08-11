# Cervical Cancer Prediction

1. For my machine learning final project, I utilized the UCI dataset on cervical cancer to conduct both binary and multiple classification tasks. Initially, I approached the binary classification by predicting the likelihood of a patient having cervical cancer based on one of the target variables: Hinselmann, Schiller, Cytology, and Biopsy. The multiple classification aimed at gauging the risk degree, given the limitation in the binary classification performance.

2. A systematic data preprocessing was undertaken which included steps such as replacing missing values represented by ‘?’ with NaN, removal of two imbalanced features, filling NaN values, standardizing the dataset, and partitioning it into an 80-20 split for training and testing. To achieve the classification, I employed models like logistic regression, SVM with a polynomial kernel, and neural networks. The initial results rendered a performance accuracy of 92% for binary classification and 91% for multiple classification.

3. Recognizing the scope for improvement in performance, an in-depth exploration of the dataset was pursued. A meticulous study of the data's background revealed a significant number of blank entries. Using objective insights from psychology and medicine, we supplemented and balanced the original data, enriching its potential to serve our classification goals.

4. Post the comprehensive data augmentation, the same methodologies from stage 1 were applied, leading to markedly enhanced results. The performance soared to 96.6% for binary classification and an impressive 98.7% for multiple classification. This tangible improvement emphasized the value of in-depth data understanding and its processing.

5. The overarching conclusion from this project was the pivotal role of data comprehension and preprocessing. The tangible boost in accuracy with unchanged models accentuated that delving deep into unfamiliar datasets, understanding the inherent nuances from specialized perspectives, and customizing the feature processing accordingly, can significantly elevate prediction accuracy.

6. Collaborated with my teammate Shangyu Xie
