# Leukemia Classification using Deep Learning & Generative AI  

## **Project Overview**  
This project focuses on classifying leukemia and breast cancer using deep learning techniques.  
- **CNN Models**: Used for image classification.  
- **GANs**: Used for synthetic data generation to address class imbalance.  
- **Evaluation**: Models tested on both leukemia and breast cancer datasets.  

---

## **Folder Structure**  

```
📂 Code  
│── 📂 leukemia-analysis  
│   ├── cnn_model_unbalanced.ipynb   # CNN trained on original dataset (imbalanced)  
│   ├── cnn_model_balanced.ipynb     # CNN trained on GAN-augmented dataset (balanced)  
│   ├── gan_model.ipynb              # GAN training to generate synthetic images  
│   ├── gan_image_generator.ipynb    # Script to generate synthetic images using trained GAN  
│  
│── 📂 breast-cancer-analysis  
│   ├── cnn_model_unbalanced.ipynb   # CNN trained on original dataset (imbalanced)  
│   ├── cnn_model_balanced.ipynb     # CNN trained on GAN-augmented dataset (balanced)  
│   ├── gan_model.ipynb              # GAN training for breast cancer dataset  
│   ├── gan_image_generator.ipynb    # Generates synthetic breast cancer images  
│  
│── 📂 cnn-architectures  
│   ├── cnn_architectures.ipynb      # Implements ResNet50, InceptionV3, EfficientNetB3  
│  
│── requirements.txt                 # Required dependencies  
│── README.md                        # Instructions (this file)  
```

---

## **Setup & Installation**  

### **1. Install Dependencies**  
Run the following command in the terminal to install required libraries:  

```bash
pip install -r requirements.txt
```

### **2. Running CNN Models**  
#### **Leukemia Analysis**  
- Run **cnn_model_unbalanced.ipynb** to train CNN on original dataset (imbalanced).  
- Run **gan_model.ipynb** to train the GAN.  
- Use **gan_image_generator.ipynb** to generate synthetic images.  
- Run **cnn_model_balanced.ipynb** to train CNN on the balanced dataset.  

#### **Breast Cancer Analysis**  
- Follow the same steps as above inside `breast-cancer-analysis/`.  

### **3. Running Different CNN Architectures**  
- Inside `cnn-architectures/`, run `cnn_architectures.ipynb` to test different CNN models (ResNet50, InceptionV3, EfficientNetB3).  

---

## **Expected Outputs**  
- **Trained CNN models** for both leukemia and breast cancer classification.  
- **Synthetic images generated using GANs** to balance datasets.  
- **Performance metrics (Accuracy, AUC-ROC, Precision, Recall, F1-Score)** stored in logs.  

---

## **Notes**  
- This project was developed as part of the **H9DLGA: Deep Learning and Generative AI** course at **National College of Ireland**.  
- All datasets used are publicly available.