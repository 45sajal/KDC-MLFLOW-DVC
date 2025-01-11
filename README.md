# Kidney Tumor Classification  

## Project Overview  
This project aims to classify kidney images into two categories: **Normal** and **Tumor**. It is a **binary classification** problem leveraging Convolutional Neural Networks (CNN) and transfer learning techniques. The model training and results were managed and logged using **MLFlow**. The solution was deployed locally using **Streamlit** for interactive testing.

---

## Dataset Description  
The dataset consists of **12,000 images**:  
- **7,000 Normal Kidney images**  
- **5,000 Tumor Kidney images**  

### Preprocessing:
1. **Image Augmentation**: Applied various augmentation techniques to enhance dataset diversity and improve model performance.  
2. **OpenCV**: Used for preprocessing tasks such as resizing, normalization, and filtering.

---

## Methodology  

### Model:  
- **Transfer Learning**: Utilized a pre-trained model **VGGNet-16** for efficient feature extraction and classification.
- Fine-tuned the model to adapt to kidney image classification.  

### Feature Engineering:  
- Applied data augmentation techniques, including rotation, flipping, and brightness adjustment, to increase dataset size and diversity.

### Modular Coding:  
- Implemented modular code architecture for better reusability and maintainability.  

---

## Tools and Technologies  
- **Python**  
- **TensorFlow/Keras** for deep learning model development  
- **OpenCV** for image preprocessing  
- **MLFlow** for model logging and tracking  
- **Streamlit** for local deployment and user interface  

## Clone the repository

```bash
https://github.com/45sajal/KDC-MLFLOW-DVC
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

## Results  
- Successfully trained the CNN model using **VGGNet-16** with high accuracy for kidney tumor classification.  
- Improved model performance through extensive preprocessing and augmentation.  

---

## Deployment  
- The final model was deployed locally using **Streamlit**, enabling users to upload images and receive predictions (Normal or Tumor).  

---

## Conclusion  
The project demonstrates the effective application of transfer learning and image preprocessing techniques for medical image classification. The use of modular coding, logging with MLFlow, and deployment via Streamlit highlights the importance of a complete pipeline in real-world scenarios.

