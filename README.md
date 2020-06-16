![Alt-Text](https://image.freepik.com/free-vector/technology-face-circuit-diagram-background_1017-18300.jpg)

# Machine Learning - A hands on approach

This Showcase is inspired by the assignments of the course "Machine Learning" which I attend this summer semester 2020. The module does not only show implementations of different learning models, but also teaches the underlying mathematical foundations. In the following, a problem will be presented and how we can solve it, including the model selection, parameter tuning and finally, the model evaluation. [Here is the full notebook](google.de)
<br><br/>
The work on these tasks has been a close collaboration with **@iwasscience**. While I polished the nuances to make this showcase presentable, we worked together to solve the assignments. If you're further interested in other Machine Learning Projects, I truly recommend you to check out his [GitHub](https://github.com/iwasscience).  
<br>
**Used technologies:** *Jupyter Notebooks, Python, Pandas, Numpy, Scikit, Tensorflow, Keras, Seaborn*
<br><br/>

## Overview
To start with, a description of our primary learning problem is given. This learning problem will serve as our motivation and guide us along the sections. Each section itself consists of the implementation and the theory behind it. Our elaboration is structured as the following: 
<br>

1. **The dataset**

2. **Learning Model**

3. **Hyperparameter Tuning**

4. **Model Evaluation**

In general, this is roughly the common approach for a machine learning problem. The result is a trained model, which is able to make profound predictions. To achieve this, we have to use the existing data to train the model and then tune and evaluate it. This is not a rigid order, as we conclude within our evaluation that we should have choosen another learning model perhaps. You get the spirit.
<br><br/>

## 1. The data set

What if a malicious villain kidnaps your loved ones and the only way to rescue them is by being able to identifiy a random flower via its sepal lenght. Fear no more, we got you fam. [The Iris flower data set](https://en.wikipedia.org/wiki/Iris_flower_data_set) is the designated data set we work with and it surely will become handy some day in your life. 
<br><br/>
![Alt-Text](https://www.spataru.at/images/blog/iris-dataset-svm/iris_types.jpg)


<br><br/>

## 2. Learning Model





<br><br/>

## 3. Hyperparameter Tuning


```python
fig, axes = plt.subplots(2, 2, figsize=(20, 10))

for clf, ax in zip(clfs, axes.ravel()):
    show_decision_function(clf, ax)
    ax.set_title(clf.name)

```

![Alt-Text](https://github.com/Ben-Ed/Machine_Learning_SS20/blob/master/Unbenannt.png)
<br><br/>

## 4. Model Evaluation

