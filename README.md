<h1>About</h1>

This is a Machine Learning notebook using the Heart Disease dataset [link](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset). This was a submission as a group project for a course in NTU, Singapore.
The numeric variables inside the dataset is first visualized here:

<p align="center">
  <img src="https://github.com/shsgResume/HeartDiseaseCollaboration/assets/167844966/9570360c-7adb-4a64-8247-93c3d1713b11" />
</p>

Afterwards, a kNN, a Logistic Regression and SVM model was made to predict multiple variables and the likelihood of an individual to suffer from a Heart Diseases.

<p align="center">
  <img src="https://github.com/shsgResume/HeartDiseaseCollaboration/assets/167844966/a6c266f7-2119-4b8d-8c0e-247a87a86010" />
</p>

The prediction correctness and the confusion matrix are shown below for kNN

```
[1] 0.6885246
knn1  0  1
   0 19 15
   1  4 23
```
<p align="center">
  <img src="https://github.com/shsgResume/HeartDiseaseCollaboration/assets/167844966/a352f7ab-fcad-47df-84eb-669096a88357" />
</p>

The prediction correctness and the confusion matrix are shown below for Logistic Regression

```
[1] 0.7213115
       
prednum  0  1
      0 22 16
      1  1 22
```

The SVM model is explored further in the notebook

<h1>Requirements</h1>

> [!NOTE]
> R<br>
> dplyr<br>
> ggplot2<br>
> caret<br>
> class<br>
> psych<br>
> coorplot<br>
> e1071<br>


