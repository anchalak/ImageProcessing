#Image Processing Projects

### This repository contains three image processesing and one image classification projects. Below is a summary of all four projects:

#### 1. Image Processing using DeOldify
In this Project, I will levarage DeOldify to colorize different types of images to get a better sense of how colorization works on diffrerent different types of images. DeOldify is a deep learning-based image colorization algorithm that aims to restore color to grayscale images. Below is a quick summary of how it works:

1. Input a grayscale image lacking color information.

2. Apply a decolorization step to remove remaining color information.

3. Utilize a GAN-based colorization model to generate a colorized version of the image.

4. Train the model on a dataset of colored images to learn colorization patterns.

5. Evaluate the colorization output for visual appeal and realism.
   
#### 2. Image Processing
In this project, I will take an image and do initial image processing. Here I will use kmeans to look at the color breakdown of an image, blur the image, increase contrast, increase brightness, and convert to greyscale.

#### 3. Anomaly Detection in Images
Here I use three different models to find anomalous digits.

1. Autoencoder: Here we implemented an anomaly detection system using autoencoders on the MNIST dataset, which consists of grayscale images of handwritten digits from 0 to 9. The goal is to detect anomalous digits (digits 7 to 9) from normal digits (digits 0 to 4) using an unsupervised learning approach.

2. Isolation Forest: he key idea behind Isolation Forest is to isolate anomalies (outliers) by constructing a tree-based partitioning of the data space. The algorithm is based on the intuition that anomalies are rare instances that can be easily separated from the majority of the data.

3. Local Outlier Factor (LOF) is another popular algorithm for anomaly detection, and it takes a different approach compared to Isolation Forest. LOF is designed to identify local anomalies, meaning instances that are outliers in their local neighborhoods rather than being global anomalies across the entire dataset.

#### 4. Image Classification
The objective of this project is to build an image classification model to classify 32x32 color images from the CIFAR-10 dataset into one of the ten classes. The CIFAR-10 dataset consists of 60,000 images across 10 classes, with 6,000 images per class. The classes are 'airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', and 'truck'.
