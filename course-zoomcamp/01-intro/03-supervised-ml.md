## 1.3 Supervised Machine Learning

<a href="https://www.youtube.com/watch?v=j9kcEuGcC2Y"><img src="images/thumbnail-1-03.jpg"></a>

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-13-supervised-machine-learning)


## Notes
In Supervised Machine Learning (SML) there are always labels associated with certain features. The model is trained, and then it can make predictions on new features. In this way, the model
is taught by certain features and targets. 

**Feature matrix (X):** made of observations (rows) and features (columns). For each row, there is a **y** associated vector of targets. 

The model can be represented as a function **g** that takes the X matrix as a parameter and tries to predict values as close as possible to y targets. 
The obtention of the g function is what it is called **training**.

### Types of SML problems 
* **Regression:** the output is a number (car's prize)
* **Classification:** the output is a category (spam example). 
	* **Binary:** there are two categories. 
	* **Multiclass problems:** there are more than two categories. 
* **Ranking:** the output is the big scores associated with certain items. It is applied in recommender systems. 

In summary, SML is about teaching the model by showing different examples, and the goal is to come up with a function that takes the feature matrix as a
parameter and makes predictions as close as possible to the y targets. 

## Navigation

* [Machine Learning Zoomcamp course](../)
* [Lesson 1: Introduction to Machine Learning](./)
* Previous: [ML vs Rule-Based Systems](02-ml-vs-rules.md)
* Next: [CRISP-DM](04-crisp-dm.md)