#  Drug Recommendation System using ResNet

This project applies **deep learning** and **API-based intelligence** to develop a system that diagnoses chest diseases from X-ray images and recommends safe medications by checking for potential drug–drug interactions.

---

##  Overview

The system performs two primary tasks:
1. **Disease Detection:**  
   Utilizes a **ResNet-based convolutional neural network** to classify chest X-rays into four categories — *Normal*, *COVID-19*, *Viral Pneumonia*, or *Bacterial Pneumonia*.
2. **Drug Recommendation:**  
   Once the disease is predicted, the system cross-verifies the patient’s medication history using a **Drug–Drug Interaction API**, ensuring that newly prescribed drugs are safe to use together.

This notebook demonstrates an end-to-end AI pipeline combining medical imaging, deep learning, and pharmacological safety validation.

---

##  Features

-  **Automated Chest X-ray Classification:** Detects and differentiates respiratory diseases using ResNet.  
-  **Drug Interaction Validation:** Integrates a real-time API to identify unsafe drug combinations.  
-  **End-to-End AI Workflow:** From image input to final safe drug recommendation.  
-  **High Accuracy Model:** Enhanced with data augmentation, normalization, and transfer learning.  
-  **Research-Focused:** Designed for clinical, research, and academic experimentation.  

---

##  Tech Stack

- **Language:** Python  
- **Frameworks/Libraries:** TensorFlow / Keras, NumPy, Pandas, Matplotlib, OpenCV  
- **Model Architecture:** ResNet (Residual Network)  
- **API:** Drug–Drug Interaction API  
- **Environment:** Google Colab  

---

##  Workflow

1. **Input:** Upload or load a chest X-ray image.  
2. **Preprocessing:** Resize and normalize images to the required model dimensions.  
3. **Prediction:** ResNet model classifies the disease condition.  
4. **Medication Input:** Patient’s existing drug list is entered.  
5. **API Check:** System queries the Drug–Drug Interaction API to verify medication safety.  
6. **Output:** Returns a list of recommended or flagged drugs based on interactions.

---

##  Results

- Achieved high classification accuracy on multiple chest X-ray datasets.  
- Demonstrated successful detection of dangerous drug interactions using API integration.  
- Showcased potential for AI-driven decision support in medical environments.

---

## ** Future Improvements**

-Expand dataset diversity for better generalization.

-Implement web or mobile interface for real-world deployment.

-Include additional diseases and drug categories.

