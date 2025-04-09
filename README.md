# Brain Tumor Classification Using Custom CNN on MRI Images

## Project Overview
This project implements a custom Convolutional Neural Network (CNN) built from scratch using TensorFlow/Keras to classify brain MRI images into four categories: glioma, meningioma, pituitary tumor, and no tumor. The model, developed and tested in a Google Colab notebook, achieves a validation accuracy of 94% and an F1-score of 91% using a retrained VGG16 model.

### Abstract
A brain tumor is an aggressive disease, with over 84,000 people diagnosed with a primary brain tumor in 2021 and an estimated 18,600 deaths from malignant brain tumors that year. Magnetic Resonance Imaging (MRI) is the best technique for detection. This project uses deep learning to identify and classify tumors into benign, malignant, or pituitary types. A dataset of 3,260 T1-weighted contrast-enhanced MRI images was preprocessed and augmented. Comparative studies of ANN, CNN, and Transfer Learning (TL) models were conducted, with the custom CNN achieving 90% accuracy, ANN 78%, and VGG16 (retrained) reaching 94% accuracy.

## Dataset
- **Folder**: `BT_dataset`
- **Structure**:
  - `Training`: Contains 4 subfolders (`glioma_tumor`, `meningioma_tumor`, `no_tumor`, `pituitary_tumor`) with training images.
  - `Testing`: Contains 4 subfolders (`glioma_tumor`, `meningioma_tumor`, `no_tumor`, `pituitary_tumor`) with testing images.
- **Download**: The dataset is hosted on Kaggle. The download link is available in `BT_dataset.txt`. Download it, unzip it into this directory, and use it with the project.
- Total images: 3,260

## Project Structure
- `Code/Brain_Tumor_Detection.ipynb`: Jupyter Notebook with the custom CNN implementation, preprocessing, and training code run in Google Colab.
- `BT_dataset.txt`: Contains the Kaggle dataset download link.

## How to Run
1. Clone this repository or download the files.
2. Download the dataset from the link in `BT_dataset.txt` and unzip it into the `BT_dataset` folder.
4. Open `Code/Brain_Tumor_Detection.ipynb` in Google Colab or a local Jupyter Notebook and run the cells.

## Results
- Custom CNN (3 layers): 90% accuracy.
- ANN: 78% accuracy.
- VGG16 (retrained): 94% accuracy, 91% F1-score.

## Tools Used
- TensorFlow/Keras
- Python
- NumPy, Matplotlib, etc.
- Google Colab

## Acknowledgments
- Dataset sourced from Kaggle.
- Inspired by advancements in deep learning for medical imaging.
