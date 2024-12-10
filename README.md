# Fashion-MNIST Classification Project

## **Overview**
This project focuses on building a Convolutional Neural Network (CNN) to classify grayscale images of clothing into 10 categories using the Fashion-MNIST dataset. The goal was to achieve high classification accuracy while adhering to deep learning best practices.

---

## **Project Structure**
The repository is organized into the following directories and files:

### **/notebooks/**
- `fashion_mnist_project.ipynb`  
  The main Jupyter Notebook containing all code, analysis, and results.

### **/slides/**
- `slide_presentation.pdf`  
  A PDF version of the project presentation.  
- `slide_presentation.pptx`  
  An editable PowerPoint version of the project presentation.

### **/images/**
- `class_distribution.png`  
  Bar plot of class distribution.  
- `pixel_intensity_histogram.png`  
  Histogram of pixel intensities.  
- `training_validation_accuracy.png`  
  Accuracy plot comparing training and validation.  
- `training_validation_loss.png`  
  Loss plot comparing training and validation.  
- `confusion_matrix.png`  
  Confusion matrix visualization.  
- `cnn_architecture.png`  
  Diagram of the CNN architecture.

---

## **Steps to Reproduce**
To reproduce this project and explore the code:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fashion-mnist-classification.git
2. Navigate to the project directory:
cd fashion-mnist-classification
3. Install dependencies:
pip install -r requirements.txt
4. Open the notebook:
jupyter notebook /notebooks/f

---

## **Dataset**

### **Source**
The dataset used in this project is the Fashion-MNIST dataset, available through [Keras Datasets](https://www.tensorflow.org/datasets/catalog/fashion_mnist).

### **Description**
Fashion-MNIST is a dataset of grayscale images of clothing items, intended as a replacement for the classic MNIST dataset. It consists of:
- 60,000 training images.
- 10,000 test images.
- Each image is 28x28 pixels, grayscale.

### **Classes**
The dataset contains 10 classes, representing different types of clothing:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

---

## **Results**
- **Training Accuracy:** ~92%
- **Validation Accuracy:** ~90%
- **Test Accuracy:** 90.42%
- **Test Loss:** 0.2718

These results demonstrate the effectiveness of the CNN architecture and the model’s ability to generalize well to unseen data.

---

## **Video Presentation**
The project video presentation is available on Vimeo:  
[**Fashion-MNIST Project Video**](https://vimeo.com/1037814359?share=copy)

---

## **Acknowledgments**
This project was made possible by the following resources:
- **Dataset:** Fashion-MNIST provided by Zalando Research.
- **Libraries and Tools:** TensorFlow, Keras, Matplotlib, NumPy, and Jupyter Notebook.
- **Video Hosting:** Vimeo for sharing the project presentation.

Special thanks to the course instructors and peers for their guidance and feedback throughout this project.
