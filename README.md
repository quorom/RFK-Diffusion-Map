# Random Forest Kernel with Diffusion Maps

The purpose of this notebook is to utilize Random Forest Kernel's as a distance
metric for Diffusion Maps.

The random forest kernel 
K(i,j) = sum of number of times i and j end at the same node of a tree / total number of trees. 
This will be come our probability matrix P in diffusion.

TODO Demonstrate the difference's by taking the MNIST dataset, performing, PCA, ISM,
Regular Diffusion Map, and the Random Forest Kernel Diffusion Map.
