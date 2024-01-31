### MNIST Fashion Classification

In this project, I was focusing on image classification using a Convolutional Neural Network (CNN) on MNIST Fashion dataset. This dataset is available on TensorFlow Datasets. I implemented a data preprocessing pipeline that loads and normalizes MNIST Fashion dataset. On this dataset I performed the followings:

- To enhance robustness, I introduced noise (noise_factor = 0.2) to both training and test images.
- Built and trained a CNN classifier, reporting accuracy for clean and noisy test images.
- Additionally, designed a CNN autoencoder to denoise the images, showcasing examples through plots, and reported classification accuracy for the autoencoder denoised test images.
- Finally, evaluated the original model's performance when trained with noisy images, reporting accuracy for noisy test images.


#### Project Details:
- Language: Python
- Dataset MNIST Fashion Dataset
- Goal: Classify images.
- Techniques: Deep Learning, Convolutional Neural Network (CNN)
- Library: TensorFlow, Keras
- Environment: Anaconda
  
