# What is machine learning
Machine learning (ML) is a field of Artificial Intelligence (AI) that allows computer programs to learn from data and construct decision models without explicitly programming them

![](https://www.oreilly.com/api/v2/epubs/9781788624336/files/assets/27c1671a-61d3-46e1-ac66-e3dbd5683ab2.png)

The picture above is a comparaison between classical programming and machine learning. In Classical programming, computers can only do what we program them to do. While with machine learning computers can gain knowledge based on previous data.

For example, social media apps use machine learning to create your feed based on your preferences.

There are three types of machine learning:
1. supervised learning
2. unsupervised learning 
3. reinforcement learning

# supervised machine learning
Supervised machine learning is used with labeled datasets to predict a target y based on features X
Now let's define these terms: 
* a target: The variable that we want to predict (output). We call all the entries of the target column labels. 
* features: All the variables other than the target (input) 
* labeled dataset: It's a dataset that consists of input and ouput that means the target variable is already known

Both features and target variables may be of different data types: 
* Numerical: values in R 
* Integer: values in Z
* categorical: values in a finite set
* binary: values in {0,1} 

Example: the `Iris` dataset is a labeled dataset that has 4 numerical features (sepal length, sepal width, petal length and petal width) and a target variable that has three classes (setosa, versicolor, and virginica)<br>
[Read more about Iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set)

There are two types of supervised learning:
* classification: target variable is discrete (can take limited values) 
* regression: target variable is continuous (for example a numerical target)

[Read more about classification and regression](https://www.datacamp.com/blog/classification-machine-learning)










