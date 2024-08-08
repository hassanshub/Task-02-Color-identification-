# Task-02-Color-identification-

This project provides a method for identifying and visualizing the dominant colors in an image using K-means clustering, a popular machine learning technique. The script performs several key steps to achieve this:

First, the image is preprocessed to ensure accurate color analysis. This involves loading the image from a specified file path and converting it from BGR (Blue, Green, Red) to RGB (Red, Green, Blue) format to correctly represent the colors. The image is then resized to a manageable dimension to speed up processing and flattened into a 2D array where each pixel's RGB values are represented as rows in the array.

Next, K-means clustering is applied to the flattened pixel data. This unsupervised learning algorithm clusters the pixels into a specified number of color groups, known as num_clusters. The algorithm identifies the central color of each cluster, which represents a dominant color in the image. This approach allows for identifying multiple prominent colors rather than just a single dominant hue.

Finally, the identified colors and their frequencies are visualized using a pie chart. This chart illustrates the proportion of each color within the image, providing an intuitive way to understand the color distribution. Each slice of the pie represents a different color, with the size of the slice corresponding to the frequency of that color.
