# Data science in Python
## Day 3: Dimension reduction methods.
### Using multi-dimensional scaling

+ Plotting a map of Europe given distances between cities
+ Using genetic distances to map ethnicity

### Looking at dimension reduction, using principal component analysis

For this exercise we use this dataset we have:
    - 228 donors, ~15000 gene expression values

The gene expression is from the innate immune cells, monocytes under 4 conditions:
    - Untreated, as a control.
    - Treated with inteferon-gamma (IFN) for 24 hours – a good model for viral infections.
    - Treated with Lipopolysaccharide (LPS) for 2 hours - LPS is a major component of the outer wall of gram negative bacteria, which our body registers as a toxin and elicits a strong immune response.
    - Treated with Lipopolysaccharide (LPS) for 24 hours.
    
So we have a dataset for 912 samples (from 228 donors for 4 conditions each), gene expression data for ~15,000 genes. 

How to understand this dataset?

No doubt there is high redundancy amongst the samples, so reducing them from ~15000 to a smaller number could be really helpful into interpreting the dataset (in this case for projecting the gene expression and genes into one value for each sample for each principal component).

### Clustering

From the gene expression data, we know that we have 4 groups. Using a k-means clustering algorithm on the PCA data; can we recover these groups?

Prerequisites
-------------

For this session, could you install the following package:

*   adjustText: [https://adjusttext.readthedocs.io/en/latest/](https://adjusttext.readthedocs.io/en/latest/) I usually use pip or conda to install packages: 
    *   pip install selenium
        
        or
    *       conda install -c conda-forge adjusttext
        

* * *

Recommended tutorial and reading
--------------------------------

*   Nice explanation of PCA can be found [here](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues).
*   And k-means clustering [here](https://realpython.com/k-means-clustering-python/).
*   The gene expression dataset we are using today and for Day 4 comes from this [paper](https://www.science.org/doi/10.1126/science.1246949).
