# Anomaly_Detection
Anomaly Detection with Neural Networks

## CNN 2-class classification
using the normal images and anomal images. With this way of solution, we need enough, balanced data amounts of normal and anomal images.

by the benchmark dataset, we got a high accuracy, but in real uses the balance of normal and anomal will not be equal so that we need to test the algorithm in much more realistic situations.

## AutoEncoder 1-class classification
using only the normal images. Train the AutoEncoder with the normal images. when prediction, it will have bigger differences between the anomal image and the decoded image rather than the normal image and decoded image.

With this way of solution, we can predict robustly in any kind of anomal types.
On the other hand, the training is quit difficult so that we need a better Encoder and Decoder to use in realistic situations.
