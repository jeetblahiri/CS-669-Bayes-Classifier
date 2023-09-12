# CS-669-Bayes-Classifier

## Classification tasks
Datasets:
Dataset 1: Linearly separable classes: 3 classes, 2-dimensional linearly separable data is
given. Each class has 500 data points.
Dataset 2: Nonlinearly separable classes: 2-dimensional data of 2 or 3 classes that are
non-linearly separable. The number of examples in each class and their order is given at the
beginning of each file.
Dataset 3: Real-world data (Vowel data): 2-dimensional data of 3. The real-world data set
correspond to the formant frequencies F1 and F2 for vowel utterances.
Divide the data from each class into training, and test data. From each class, train, and test split
should be 70% and 30% respectively.
Assumption: Class-conditional densities are Gaussian
Classifiers to be built for each dataset: Bayes classifier.
1. Covariance matrix for all the classes is the same and is σ2
I.
a. You can obtain the same covariance matrix for all the classes by taking the average of
covariance matrices of all the classes. You can obtain the same variance by averaging all
the variances.
2. Full Covariance matrix for all the classes is the same and is Σ.
a. You can obtain the same covariance matrix for all the classes by taking the average of
covariance matrices of all the classes.
3. Covariance matric is diagonal and is different for each class.
4. Full covariance matrix for each class is different.

## Presentation of results: 
Report should include the results of studies presented in the following
forms for each classifier and for each dataset.
1) Confusion matrix, classification accuracy, precision for every class, mean precision, recall for
every class, mean recall, F-measure for every class and mean F-measure on test data.
2) Constant density contour plot for all the classes together with the training data superimposed.
3) Decision region plot superimposed by training data only for each of the datasets. Give the
decision region plot between each pair of classes and also, give the decision region plot all
classes together (only if the number of classes are more than 2).
4) Inferences on the plots and inferences on the results observed (such as performance, nature of
decision surface etc.) for each dataset.
