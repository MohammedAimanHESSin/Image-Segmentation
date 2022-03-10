# Image-Segmentation-Problem
We will group similar pixels together and give these grouped pixels the same label.

## Methods of Segmentation

### 1. K-means
- We will change the K of the K-means algorithm between {3,5,7,9,11} clusters, and produce different segmentations and save them as colored images. 
Every color represents a certain group (cluster) of pixels.

- We will evaluate the result segmentation using **F-measure**, **Conditional Entropy** for image I with M available ground-truth segmentations. 

- Display good results and bad results for every configuration.

### 2. N-cut
- Repeate the same of k-means procedure.

## Data-Set

We will use Berkeley Segmentation Benchmark. 
- A large dataset of natural images that have been manually segmented. 
- The human annotations serve as ground truth for learning grouping cues as well as a benchmark for comparing different segmentation and boundary detection algorithms.
- The dataset has 500 images: 200 image for trainning , 200 for validation and 100 for test. 
- The data is available at the following **[link](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/BSR_bsds500.tgz)**. 

## Results
- 
