# iris-dataset
This repository help understanding the iris dataset
## datasets.load_iris()
**iris** dataset is a type of simple and classic dataset used for learning machine learning and sata analyses.
It is a type of measurment of 150 flowers.
There are 3 species of the this flower and 50 flowers from each : ****Setosa**** ,****versicolor****,****virginica**** 
which are the target values.
These types are predicted based on 4 features :
- Sepal length
- Sepal width
- Petal length
- Petal width
## Common task : 
precidt the specie based on its measurements.The terget is a **natural classification** based on combination of all 4 features.

## How the features are related to the target
If you plot the data you can see clear patterns that define the conditions for each species.


 1.**Setosa** is the easiest to identify
   `petal length ` and `petal width ` are smaller than other epieces.
    `if petal length < 2 ` then it is absolutely **setosa** . 

2.**Versicolor** vs  **Virginica** : these two are closer and overlap a bit
 **Overall condition:** versicolor has smaller `petal_width` than  **Virginica**.
  versicolor typically has smaller `petal_length` than  **Virginica**
  **Virginica** is on the moddle range.

I found the data set from this website :
  https://gist.github.com/curran/a08a1080b88344b0c8a7
