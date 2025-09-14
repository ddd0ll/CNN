# CNN
Image Classification with CNN (CIFAR-10)

This project trains a convolutional neural network (CNN) with PyTorch to classify images from the CIFAR-10 dataset into 10 categories: airplane, car, bird, cat, deer, dog, frog, horse, ship, and truck.  

 Technologies used:
- Python 3  
- PyTorch  
- Torchvision  
- Google Colab (with GPU acceleration)  
- Matplotlib / NumPy  

 Dataset
The CIFAR-10 dataset was used, which contains:  
- 60,000 color images of 32x32 pixels.  
- 50,000 images for training.  
- 10,000 images for testing.  
- 10 different classes.  

(The dataset is automatically downloaded from torchvision.datasets).

Main steps
1. Data loading and preprocessing (normalization and data loaders).  
2. Definition of the CNN with convolutional layers, ReLU, MaxPooling, and fully connected layers.  
3. GPU training with Adam and CrossEntropyLoss.  
4. Model evaluation on the test set.  
5. Visualization of predictions on real images.  

 Results:
- Accuracy obtained in test: ~70% (may vary depending on training).  

How to use it
 1. Clone the repository
bash git clone https://github.com/TU-USUARIO/cnn-cifar10.git
cd cnn-cifar10
