# Feature-Engineering-car-price-
##This is a demonstration of what I've learnt in feature engineering and how I used them to build features with better MI scores


##In this notebook, I've gone through multiple feature engineering techniques, from mathematical transforms to unsupervised learning methods(Clustring with HDBSCAN) to variation analysis(PCA) to target encoding

##TTarget Encoding
###This is a type of encoding process for a categorical variable where the encoding is done based on the target attribute and it's relationship to the categorical attribute. When this is being applied in an actual ML program, care must be taken to precent target leaklage and overfitting

##Mathematical transform:
###Here, we've built our own features from exitsting features by simple mathematical operations(like 'avg_mpg' from 'min_mpg' and 'max_mpg')

##Clustering
###We've used HDBSCAN(Hierarchical Density-Based Spatial Clustering of Applications with Noise) for density based clustering of clusters of varying density. This type of clustering could potentially allow the model to learn the complex relationships between the data points easier

##PCA
###Here, we've formed PCA features from intial features, whcih maps the variation of the initial features along certain axes, thus allowing us to learn the compex relationships of the model easier. These features and their loadings can then be analysed to form new features or these PCA features can be used themselves directly. Care must be taken when considering PCA features, so as to prevent overfitting

##Note : This isn't a best practices notebook or a process to follow step by step, but merely me experimenting with different feature engineering techniques and how it affects a dataset. When applying such techniques, care must be taken to prevent overfitting to ensure a generalised and strong model

#By : Karthik Sabareesh
#Github: https://github.com/KarthikSabareesh
