# 🧠 Hybrid Deep Learning Architectures for EEG-based Schizophrenia Detection

This section presents visualizations supporting the research titled:  
**"A Comparative Analysis of Hybrid Deep Learning Architectures for Detecting Schizophrenia from EEG Signals"**

In this study, EEG signals were used to develop and evaluate several deep learning models—1D-CNN, GRU, CNN-LSTM, CNN-GRU, CNN-SVM and CNN-LSTM-GRU—for classifying schizophrenia patients from healthy controls. The models were trained on preprocessed EEG datasets and assessed based on accuracy, loss, and ROC curve performance. Activation functions like ReLU and ELU were also compared to determine their impact on classification efficiency.

The figures below illustrate the architecture, training behavior, and classification performance of each model variant.


---

## Abstract

Schizophrenia (SZ) is a severe mental health disorder where objective and automated detection methods can support early diagnosis and treatment. This project proposes a novel triple-hybrid deep learning architecture (CNN–LSTM–GRU) for automated schizophrenia detection using electroencephalogram (EEG) signals.

The proposed model leverages the complementary strengths of Convolutional Neural Networks (CNNs) for spatial feature extraction and recurrent networks (LSTM and GRU) for learning temporal dependencies in EEG data. By integrating CNN, LSTM, and GRU into a unified framework, the model effectively captures complex spatiotemporal EEG patterns associated with schizophrenia.

The approach is evaluated on EEG recordings from 81 subjects (49 schizophrenia patients and 32 healthy controls). A comprehensive comparative analysis is performed against multiple baseline and hybrid models, including CNN, GRU, CNN–GRU, CNN–LSTM, and CNN–SVM.

Experimental results show that the proposed CNN–LSTM–GRU model achieves the highest classification accuracy of 97.04%, outperforming CNN–GRU (96.26%), standalone GRU (96.62%), and all other comparison models. These results demonstrate the effectiveness and novelty of the triple-hybrid architecture in identifying EEG biomarkers of schizophrenia.

This work highlights the potential of advanced hybrid deep learning models to improve EEG-based schizophrenia detection and contribute to more reliable and automated mental health diagnostic systems.

---

## 📌 Methodology Overview

<p align="center">
  <img width="521" height="197" alt="Methodology" src="https://github.com/user-attachments/assets/fdaad86b-95be-4146-a57c-fb6e8c022864" />
</p>

---

## 📈 GRU Model – Accuracy & Loss

<p align="center">
  <img width="400" src="https://github.com/user-attachments/assets/c6f3b46f-d7b2-4124-8120-170e6f6c086d" alt="GRU Accuracy"/>
  <img width="400" src="https://github.com/user-attachments/assets/647ac4e4-945e-475d-b660-ff11a1c365bd" alt="GRU Loss"/>
</p>

---

## 📊 CNN + GRU Model – Accuracy & Loss

<p align="center">
  <img width="400" src="https://github.com/user-attachments/assets/372350fb-38a5-41fe-adbf-ade0cf27294c" alt="CNN-GRU Accuracy"/>
  <img width="400" src="https://github.com/user-attachments/assets/702c1904-7c33-4e5b-b7ea-bd293ea38f7f" alt="CNN-GRU Loss"/>
</p>

---

## 🔁 CNN + LSTM + GRU Model – Accuracy & Loss

<p align="center">
  <img width="400" src="https://github.com/user-attachments/assets/9b273361-d9fb-495f-9f0a-e73ca11dc9a7" alt="CNN-LSTM-GRU Accuracy"/>
  <img width="400" src="https://github.com/user-attachments/assets/0183a446-a8a1-4e22-b43a-5414b84ac62e" alt="CNN-LSTM-GRU Loss"/>
</p>

---

## 📉 ROC Curve Comparison by Activation Function

### 🔹 ReLU

<p align="center">
  <img width="425" height="351" alt="ReLU ROC" src="https://github.com/user-attachments/assets/b865171b-0bbb-4348-af6a-35016b25eba4" />
</p>

### 🔸 ELU

<p align="center">
  <img width="428" height="348" alt="ELU ROC" src="https://github.com/user-attachments/assets/04ebeb26-e838-47ac-96be-eafbaad0802a" />
</p>

---
## 📊 Overall Performane

<p align="center">
<img width="480" height="228" alt="Image" src="https://github.com/user-attachments/assets/e6a254c2-ef60-49bf-809d-eea676dd29b9" />
</p>

---
## 🧠 Models Used

- 1D-CNN
- GRU
- CNN-LSTM
- CNN-GRU  
- CNN-SVM
- CNN-LSTM-GRU  

---

## 📌 Notes

- This repository focuses on **visual and experimental results only**
- The code implementation is part of the associated research work
- Figures are intended for **journal/conference publication support**

---
## 📬 Contact

**Author:** Abu Omayed  
📧 **Email:** abuomayed@gmail.com  

---
## 📜 License

This project is for **academic and research purposes only**.
