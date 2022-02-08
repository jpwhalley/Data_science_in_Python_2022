# Data Science in Python
## Day 4: Neural networks in Python

Carrying on from yesterday, we will look to use the feature-rich, gene expression data to practise classification using neural networks. Can we accurately classify the samples to the experimental conditions based on their gene expression?

Using the follow neural networks:

+ Dense layers, no loss
+ Dense layers, with loss
+ Convolutional layer with loss

Prerequisites
-------------

For this session, you will need:

*   Keras [https://keras.io/](https://keras.io/) - I usually use pip or conda to install packages: 
    *   pip install keras
        

or

*   *   `conda install -c conda-forge keras`

Hopefully running the following works.

*   *   import keras 
        

If not you may need to install TensorFlow. You can do so, with the following command:

*   *   pip install \--upgrade tensorflow
        

*   h5py - I usually use pip or conda to install packages: 
    *   pip install h5py
        

or

*   *   conda install h5py
        

Recommended tutorial and reading
--------------------------------

*   Interesting article on interpreting neural networks [here](https://distill.pub/2018/building-blocks/).
*   Your Oxford single sign on does give you access to  [LinkedIn Learning](https://skills.it.ox.ac.uk/linkedin-learning), with two courses which may be of interest on deep learning, [this introduction](https://www.linkedin.com/learning/building-deep-learning-applications-with-keras-2-0?u=76177458) and [this follow up](https://www.linkedin.com/learning/deep-learning-image-recognition?u=76177458).
*   The Sepsis gene expression data comes from this [study](https://www.sciencedirect.com/science/article/pii/S2213260016000461?via%3Dihub).
*   An article on the downfalls of too small datasets to make valid models: [No, Scientists Have Not Found the ‘Gay Gene’ by Ed Yong](https://www.theatlantic.com/science/archive/2015/10/no-scientists-have-not-found-the-gay-gene/410059/).
