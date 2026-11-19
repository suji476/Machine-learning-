# Machine-learning-
Recognizing CIFAR-10 Images with Deep Learning

1. Project Description

This project uses Deep Learning to recognize and classify images from the CIFAR-10 dataset. A Convolutional Neural Network (CNN) is used to identify different objects in images.

2. Dataset

The CIFAR-10 dataset contains 60,000 color images of size 32 × 32 pixels divided into 10 classes.

- Training Images: 50,000
- Testing Images: 10,000
- Image Size: 32 × 32 pixels
- Number of Classes: 10

Classes

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

3. Technologies Used

- Python
- Deep Learning
- Keras
- TensorFlow
- NumPy
- Matplotlib
- CNN (Convolutional Neural Network)

4. Project Workflow

1. Import required libraries.
2. Load the CIFAR-10 dataset.
3. Display sample images.
4. Perform one-hot encoding.
5. Normalize image data.
6. Build a Sequential CNN model.
7. Compile the model.
8. Train the model for 20 epochs.
9. Evaluate the model using test data.
10. Display accuracy and loss graphs.

5. Model Architecture

The model contains:

- Convolutional Layer
- ReLU Activation
- Max Pooling Layer
- Dropout Layer
- Flatten Layer
- Fully Connected Dense Layer
- Softmax Output Layer

6. Model Configuration

- Batch Size: 128
- Epochs: 20
- Validation Split: 20%
- Number of Classes: 10
- Optimizer: RMSprop
- Loss Function: Categorical Crossentropy

7. How to Run the Project

1. Install Python and required libraries.
2. Open Jupyter Notebook.
3. Load the project notebook.
4. Run all cells sequentially.
5. The model will train and evaluate the CIFAR-10 images.

8. Expected Output

- Display sample CIFAR-10 images.
- Train the CNN model.
- Display training and validation accuracy graphs.
- Display training and validation loss graphs.
- Display test loss and test accuracy.

9. Conclusion

This project demonstrates how Deep Learning and CNN can be used for image classification. The model learns image features and classifies images into 10 different categories using the CIFAR-10 dataset.
