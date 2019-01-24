# Coursera - Practical Machine Learning - Course Project

## Introduction

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. 

In this [project](https://www.coursera.org/learn/practical-machine-learning/supplement/PvInj/course-project-instructions-read-first), the goal is creating a model to predict the manner in which they did the exercise. To do so, we are going to use the data from the study about [Qualitative Activity Recognition of Weight Lifting Exercises](http://groupware.les.inf.puc-rio.br/public/papers/2013.Velloso.QAR-WLE.pdf) [1] that register the accelerometers on the belt, forearm, arm, and dumbell of 6 participants. In this study, the participants were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information about this data is available on  and more details about it can be access by this website [http://groupware.les.inf.puc-rio.br/har](http://groupware.les.inf.puc-rio.br/har), in the section on the Weight Lifting Exercise Dataset. The result of this project is available on this [github project](https://github.com/thiagomata/CourseraPracticalMachineLearningCourseProject) that can be better visualized on the [github page](https://thiagomata.github.io/CourseraPracticalMachineLearningCourseProject/)

## Assignment

As said previously, the goal of your project is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. To do so, it is allowed to use any of the other variables to predict with. This paper must report how built the created model, how were used the cross validation, what is the expected out of sample error, and the cause of the choices maded. After that, it must present the prediction result of the model over 20 different test cases.

## Details

The R code and details about how this project works can be found on the [Project.Rmd](Project.Rmd). The code with the execution result of that can be found on the [Project.html](https://thiagomata.github.io/CourseraPracticalMachineLearningCourseProject/Project.html) and [Project.pdf](Project.pdf).

## Result

Was created a voting with weigth mechanism that uses all the generated models with accuracy bigger or equal of 80%.

The result comparing with the validation data is:

### Overall Statistics

#### Accuracy:	0.9831633
#### 95% CI:	( 0.9764356 , 0.9764356 )
#### No Information Rate:	0
#### Kappa:	0.9786948
#### Mcnemar’s Test P-Value:	NaN

## Preditictions on the Test Dataset

The result of the prediction on the test dataset is

```
  B A A A A E D B A A B C B A E E A B B B
```

## Biografy

[1] Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human ’13) . Stuttgart, Germany: ACM SIGCHI, 2013.
