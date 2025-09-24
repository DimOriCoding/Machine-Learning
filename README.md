# Machine-Learning
This folder was created as part of the "Machine Learning" course of the "Information and Communication Technologies" master's program of the Department of Informatics and Telecommunications of the National and Kapodistrian University of Athens.
Through this postgraduate course, work was carried out on the following applications implemented through machine learning algorithms:
1. [**Face Recognition**](https://github.com/DimOriCoding/Machine-Learning/blob/main/Face_Recognition.ipynb)
The Principal Component Analysis (PCA) method is iused, which is a method of compressing an initial data set (redefining its coordinates in another coordinate system that will be more suitable for the upcoming data analysis) in order to retain as much information as possible in a smaller number of dimensions, and then the nearest neighbor algorithm (k=1) algorithm with Euclidean distance as a metric for face recognition.

2. [**Image classification using Support Vector Machines (SVMs)**](https://github.com/DimOriCoding/Machine-Learning/blob/main/Face_Recognition.ipynb)
More specifically, the performance of the SVM algorithm for recognizing handwritten digits (from 0 to 9) is investigated. Essentially Support Vector Machine (SVM) is a supervised machine learning algorithm which tries to find the best boundary (hyperplane) that separates different classes (for example handwritten digits from 0 to 9) in the data. The main goal of SVM is to maximize the margin between classes. The larger the margin the better the model performs on new and unseen data.

3. [**Predicting music genres from music signals using neural networks**](https://github.com/DimOriCoding/Machine-Learning/blob/main/Music_Genre_Prediction.ipynb)
More specifically,  a 1-second music signal is classified into the following genres: classical music, pop, rock, and blues. For each 1 second, two different audio signal representations are used: 
(i) MFCCs, which are power spectrum coefficients transformed based on the mel scale, a scale that is close to the way humans perceive sound signals through hearing.
(ii) mel-spectograms: A spectrogram is a two-dimensional representation that shows the temporal evolution of the frequency spectrum. If we apply the mel scale to the spectrogram, we get the mel-spectrogram or melgram, which is used to predict music genres.
The classifier created for the purpose of predicting music genres is evaluated for its ability to generalize to real-world data that it has not been trained on,
such as YouTube videos. 
