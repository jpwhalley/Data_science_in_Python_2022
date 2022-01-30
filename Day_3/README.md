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