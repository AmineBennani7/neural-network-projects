# Neural Network Projects

This repository contains three different neural network projects. These exercises have been important for me to learn about neural networks during my studies at university.

## 1. Celsius to Fahrenheit Conversion with a Simple Neural Network

### Description
This project involves creating a simple neural network to convert temperatures from Celsius to Fahrenheit.
- **Input Layer:** Receives the temperature in Celsius.
- **Output Layer:** Produces the temperature in Fahrenheit.

### Technical Details
- **Model Architecture:** A basic feedforward neural network with only an input layer and an output layer.
- **Training Data:** A set of temperature values in Celsius and their corresponding Fahrenheit values.

### Pros
- Simple and easy to understand.
- Efficient for solving the specific problem of temperature conversion.

### Cons
- Limited to problems where the relationship between input and output is simple and linear.
- Does not generalize well to more complex tasks.

---

## 2. Clothing Classification with a Traditional Neural Network

### Description
This project involves classifying images of clothing items using a traditional neural network. The network relies on fully connected layers with ReLU activation functions.

### Technical Details
- **Model Architecture:** A feedforward neural network with fully connected layers.
- **Activation Functions:** ReLU for hidden layers.
- **Dataset:** Images of clothing items from the Zalando dataset.

### Pros
- Simple and fast to implement.
- Effective for classification tasks with a moderate number of features.

### Cons
- **Accuracy Issues:** The model may incorrectly classify images not related to clothing or misclassify personal photos of clothing. This is due to traditional neural networks treating each pixel as a distinct feature, which can limit their ability to generalize well from image data.

---

## 3. Clothing Classification with CNN, Dropout, and Data Augmentation

### Description
This project employs a Convolutional Neural Network (CNN) for clothing classification, incorporating dropout and data augmentation techniques to improve performance .

### Technical Details
- **Model Architecture:** A CNN with convolutional layers, pooling layers, dropout for regularization, and data augmentation to enhance the dataset.
- **Data Augmentation:** Includes transformations such as rotation, scaling, and shifting to artificially increase the size and variability of the training dataset.

### Pros
- **Improved Accuracy:** CNNs are specifically designed for image data, allowing for better feature extraction and classification.
- **Flexibility:** Can handle images of clothing, including personal photos, better than traditional neural networks.

### Cons
- **Complexity:** More complex to implement and requires more computational resources.
- **Training Time:** Longer training times due to the increased model complexity and data augmentation.

---

