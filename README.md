# Anomaly-Detection-using-Vision-Language-Models
This is my submission for SRE on the topic Anomaly Detection using Vision Language Models. CLIP has been used to extract image features to detect anomalies. \
Algorithm 
1. Extracting CLIP features of CIFAR-10 images.
2. Apply TSNE dimensionality reduction on the 512 dimensional CLIP features to retain only 2 features.
3. Modelling a multivariate Gaussian using these features and calculating probabilities of the test images being sampled from the multivariate Gaussian.
4. Classifying the lowest probability image as an anomaly.
The.ipynb notebook contains the python implementation of the following algorithm. \
The train and test images used have also been uploaded. \
The TSNE plot is also provided as a .png file.
