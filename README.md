# 🐱🐶 Cats vs Dogs Classification
This implements a Convolutional Neural Network (CNN) to classify images of cats and dogs using TensorFlow/Keras.

## 📂 Dataset
- Dataset: [Cats and Dogs Image Classification](https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification)
- Includes training and testing images:
  - **Cats**
  - **Dogs**

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Zipfile (for extracting dataset)
- Matplotlib

## ⚙️ Model Architecture
- **Input Layer:** (256, 256, 3) images  
- **Conv2D + ReLU + BatchNormalization + MaxPooling** layers  
- **Flatten Layer**  
- **Dense Layers:** 128 → 64 neurons with Dropout  
- **Output Layer:** 1 neuron with **sigmoid activation** for binary classification  

## ScreenShots
<img width="1506" height="802" alt="image" src="https://github.com/user-attachments/assets/d50c84f8-fa40-401f-a144-492e078dba96" />
<img width="1090" height="743" alt="image" src="https://github.com/user-attachments/assets/6c03dc7e-1902-4440-b176-74db6b974b94" />
