# Random Forest Kernel with Diffusion Maps

### Summary
These notebooks demonstrate the effectiveness of combining random forest kernels (RFKs) with Diffusion Maps. The idea is to use RFK over the standard Gaussian Kernel to better construct the _conectivity_ between data points.
We find this worth investigating based on the fact that random forest kernels take into account connection that may not be spatially defined by using a trained classifier, potentially giving an edge to the 
typical Gaussian kernel.

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

More details can be found [here](https://rmarcus.info/blog/2017/10/04/rfk.html).

### Diffusion Map Implementation
![screencapture-localhost-8888-notebooks-Diffusion-Map-ipynb-2022-04-06-20_31_54](https://user-images.githubusercontent.com/8800441/162114845-954e29d3-fc4c-492e-a06c-19062b92fa56.png)


### RFK w/ Diffusion Map Implementation
![screencapture-localhost-8888-notebooks-RFK-Diffusion-Map-ipynb-2022-04-06-20_30_46](https://user-images.githubusercontent.com/8800441/162114725-b1080817-9c15-43f7-839f-30c179d7967a.png)
