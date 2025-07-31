Brain Tumor Classification using DeepLabV3+

📌 Project Overview

This project focuses on classifying brain tumors using a semantic segmentation model based on DeepLabV3+, a state-of-the-art deep learning architecture. The aim is to accurately identify and classify brain tumors from MRI images using deep learning techniques.

📂 Files and Descriptions

| File Name                            | Description                                                                          |
| ------------------------------------ | ------------------------------------------------------------------------------------ |
| **Brain Tumor Classification.ipynb** | Main notebook implementing the DeepLabV3+ model, training procedure, and evaluation. |
| **Accuracy vs loss.png**             | Training history plot showing model accuracy and loss per epoch.                     |
| **Confusion matrix.png**             | Confusion matrix showing classification results across classes.                      |
| **Sample.png**                       | Sample prediction output showing tumor segmentation and classification.              |

📊 Dataset

The dataset used for this project consists of MRI brain scan images with annotated tumor regions.

➤ Dataset Details:

Source: https://drive.google.com/file/d/1kccavhwX-AqyplYyul-9z2KOI7NrlBBS/view?usp=drive_link (Download the dataset from this link)

Classes:

No Tumor

Glioma

Meningioma

Pituitary Tumor

Format: JPEG/PNG MRI images with corresponding segmentation masks (for supervised training)

➤ Structure (example):

Dataset/

├── Train/

│   ├── Images/

│   └── Masks/

├── Test/

│   ├── Images/

│   └── Masks/

✅ Requirements

Install dependencies using:

pip install tensorflow matplotlib numpy opencv-python scikit-learn

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/brain-tumor-classification.git
cd brain-tumor-classification

Place the dataset in the Dataset/ directory as described above.

Open Brain Tumor Classification.ipynb in Jupyter Notebook or Colab.

Run all cells to train and evaluate the model.

