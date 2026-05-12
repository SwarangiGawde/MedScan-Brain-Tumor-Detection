# MedScan – Brain Tumor Detection

A web application that uses machine learning and deep learning to detect 
the presence of brain tumors from MRI images uploaded by the user.

## About the Project
Brain tumor detection typically requires expert radiologists and can be 
time-consuming. MedScan simplifies this by allowing users to upload an 
MRI scan and instantly receive a prediction powered by a trained deep 
learning model.

## Tech Stack
- Python
- Flask (web framework)
- TensorFlow / Keras (deep learning)
- HTML & CSS (frontend)

## Features
- Upload MRI images directly through the web interface
- Predicts whether a brain tumor is present or absent
- Simple and user-friendly design
- Two trained models included (standard and categorical classification)

## Project Files
| File | Description |
|------|-------------|
| `app.py` | Main Flask application |
| `mainTrain.py` | Model training script |
| `mainTest.py` | Model testing script |
| `BrainTumor10Epochs.h5` | Trained model (binary) |
| `BrainTumor10Epochs Categorical.h5` | Trained model (categorical) |

## Dataset
Brain MRI Images for Brain Tumor Detection
Source: Kaggle — (https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data)

## How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the app: `python app.py`
4. Open your browser and go to `http://localhost:5000`

## Developed By
Swarangi Gawde 
