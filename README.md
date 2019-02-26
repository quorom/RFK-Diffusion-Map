# Random Forest Kernel with Diffusion Maps

### Summary
These notebooks demonstrate the effectiveness of combining random forest kernels (RFKs) with Diffusion Maps. The idea is to use RFK over the standard Gaussian Kernel to better construct the _conectivity_ between data points.

## Examples:
### IRIS Dataset
Include Images and Metrics
PCA
LDA
Diffusion with a Gaussian Kernel
Diffusion with Random Forest Kernel

### Random Forest Kernel
K(i,j) = sum of number of times i and j end at the same node of a tree / total number of trees. 
This will be come our probability matrix P in diffusion.

