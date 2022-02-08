# Data Science in Python
## Day 2: Working with data in Python

Having got the data, it is the moment to begin getting our hands dirty with data analysis. We will study two packages: [NumPy](http://www.numpy.org/) is the fundamental numeric computing and linear algebra package in Python, that allows for decent data analysis. We will learn it not only for the data analysis, but more importantly because it will be a package that will be always present in our `import` section as scientists. After NumPy we will go to [Pandas](http://pandas.pydata.org/). Pandas is a dedicated data analysis package with a lot more functionalities than NumPy, making our life much easier in terms of data visualization and manipulation.

## Machine learning in Python

On a small dataset we will go through the typical pipeline of a real Machine Learning project: start with statistical summaries and visualization of the data, build multiple different machine learning models, use cross-validation to estimate their accuracies, select the best algorithm, make and evaluate the predictions on a validation set. 
At the end of the session, we might have a look at the other useful functions integrated into scikit-learn

With thanks to Irina Chelysheva

Prerequisites
-------------

For this session, you should already have the needed packages installed.

* * *

Recommended tutorial and reading
--------------------------------

*   Today we will be learning about classification using machine learning. However, it is a very similar process to doing regression in Python. Here is a [nice tutorial on regression](https://adataanalyst.com/scikit-learn/regression-scikit-learn/) if you would like to do this instead of classification.

* * *

Optional tutorial and reading
-----------------------------

Slightly out of the scope for this course, but there are various ways to optimise your code. Especially important for very large datasets and computationally intensive task. Numba can work very nicely within Python to get similar speeds to Fortran and C++:

*   A quick guide to numba can be found [here](https://numba.readthedocs.io/en/stable/user/5minguide.html).
*   A nice article on time (and energy impact) to do computational tasks can be found [here](https://www.nature.com/articles/s41550-021-01342-y.epdf?sharing_token=D6WDBKpfOOcWHERGZz4AbtRgN0jAjWel9jnR3ZoTv0Pc7q-oiK1_CxsdnLnqzBdV9-Xj6CQQ98qvVv9fAgz7ySxWpoPJr5C4XgOXuetbs26fddzM8jDAaP_RUyzuPDdOG_uCV2N67FsOGrLM5IQku9K2si3Kw7cSPET-ES0qGQc%3D).
