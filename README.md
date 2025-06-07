# Automated Radiology Report Generation from Chest X-rays

## 📌 Project Overview
This project focuses on automating the generation of radiology reports from chest X-ray images using deep learning. The system is designed to assist radiologists and clinicians by producing coherent, clinically relevant reports that adhere to standard radiology format. It aims to address the growing demand for medical imaging interpretation, reduce diagnostic delays, and enhance healthcare delivery, especially in resource-constrained environments.

## ⚙️ Features
- 📷 **Image Input Handling**: Accepts DICOM/PNG/JPG format X-ray images.
- 🧠 **Deep Learning-Based Report Generation**: Uses a CNN+LSTM encoder-decoder model with attention mechanism.
- 📝 **Structured Report Output**: Generates outputs in typical sections — *Findings* and *Impression*.
- ⚡ **Real-Time Processing**: Capable of producing outputs in seconds for high-volume use.

## 🧪 Tech Stack
- **Programming Language**: Python
- **Libraries/Frameworks**: PyTorch, OpenCV, NLTK, Scikit-learn, Matplotlib
- **Model Architecture**: CNN (for visual feature extraction) + LSTM with Attention (for text generation)
- **Dataset**: Indiana University Chest X-ray (IU-CXR) Dataset
- **Evaluation Metrics**: BLEU

## 🏥 Dataset
- **Name**: IU-CXR (Indiana University Chest X-rays)
- **Contains**: 7,470 frontal chest X-rays with corresponding radiology reports.
- **Source**: [Open-I Dataset](https://openi.nlm.nih.gov/)

## 🧩 Functional Requirements
- **Input**: Chest X-ray image (.png/.jpg/.dcm)
- **Output**: Structured radiology report text
- **Sections**: `Findings`, `Impression`

## 🚀 How to Run

1. **Clone this repository:**
    ```bash
    git clone https://github.com/bhargavis19/Automated-Radiology-Report-Generation-from-Chest-X-rays.git
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## ✅ Evaluation Metrics
- **BLEU**: Precision-based metric for text generation


## 🧑‍⚕️ Target Users
- Radiologists
- Clinical Technicians
- Healthcare IT teams
- Researchers in Medical AI

## 📈 Potential Impact
- Reduce radiologist workload
- Provide faster diagnosis in high-volume hospitals
- Enable diagnostic support in under-resourced healthcare regions
- Improve consistency and objectivity in radiology reporting

## 🔐 Ethical Considerations
- Ensure patient privacy and data security.
- Reports are assistive and **not a substitute for expert medical opinion**.

## 📚 References
- [IU-CXR Dataset](https://openi.nlm.nih.gov/)
- Jing, B., Xie, P., & Xing, E. (2018). On the Automatic Generation of Medical Imaging Reports. *ACL 2018*.
- Zhang, Y. et al. (2020). When Radiology Report Generation Meets Knowledge Graph.
