#TASK 3
# Emotion Detection Through Voice

![Screenshot 2025-01-02 092907](https://github.com/user-attachments/assets/97bf92c5-2f0a-4a23-af0b-99cd09a308da)


This project focuses on detecting human emotions from voice data using machine learning. The model processes audio files to classify emotions such as **angry**, **sad**, **happy**, **fear**, and **surprise**. It supports both pre-recorded voice notes and real-time voice uploads, specifically designed for female voices.


## Introduction
The goal of this project is to build a machine learning model capable of detecting emotions through audio signals. By leveraging advanced audio processing and diverse datasets, the system achieves reliable emotion recognition.

---

## Libraries Used
The following libraries were used to build and implement the project:

- **Librosa**: Audio signal analysis and feature extraction.
- **Audio Libraries**: For handling audio files.
- **Keras**: For building and training deep learning models.
- **NumPy, Pandas**: For numerical operations and data manipulation.
- **Matplotlib, Seaborn**: For data visualization.

![Screenshot 2025-01-02 131743](https://github.com/user-attachments/assets/e63dd46e-c1ae-4d36-828b-4a59ac352d70)


---

## Datasets
The project utilized the following datasets for training and evaluation:
- **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**
- **CREMA-D (Crowd-sourced Emotional Multimodal Actors Dataset)**
- **TESS (Toronto Emotional Speech Set)**
- **SAVEE (Surrey Audio-Visual Expressed Emotion)**

These datasets were combined to ensure diversity and robustness.

---

## Data Exploration and Visualization
- **Emotion Distribution**: Visualized the count of emotions in the dataset to ensure balance.
- **Waveplots**: Generated waveforms for each emotion to study audio signal patterns.
- **Spectrograms**: Visualized frequency and intensity variations over time for deeper insights.

![Screenshot 2025-01-02 130743](https://github.com/user-attachments/assets/e182391d-0c8b-4a2d-9f96-86b48cedc39c)


---

## Data Preprocessing and Augmentation
### Steps:
1. **Data Cleaning**: Standardized audio files to a uniform format and duration.
2. **Data Augmentation**: Applied techniques like:
   - Pitch Shifting
   - Time Stretching
   - Adding Background Noise
3. **Feature Extraction**: Extracted features such as:
   - Mel-frequency cepstral coefficients (MFCCs)
   - Chroma features
   - Spectral contrast

---

## Model Building and Training
The deep learning model was built using the **Keras Sequential API** with the following architecture:
- **Convolutional Neural Networks (CNN)** layers for feature extraction.
- **Dense Layers** for classification.

### Training:
- **Hyperparameters**:
  - Learning Rate: Optimized for best performance.
  - Batch Size: Chosen based on dataset size.
  - Epochs: Determined through experimentation.

 ![Screenshot 2025-01-02 130638](https://github.com/user-attachments/assets/a7b40a87-e0b4-405b-a0ff-0d54deae7a45)

---

## Model Performance
- **Accuracy**: The model achieved an overall accuracy of **75%**.
- **Loss and Accuracy Plots**: Training and validation loss were visualized to monitor model performance over epochs.

![Screenshot 2025-01-02 130619](https://github.com/user-attachments/assets/634895b3-aec1-4cbb-a021-8d4fb9015a22)


---

## Conclusion
This project successfully implemented a system for emotion detection through voice. It demonstrated the potential of audio-based emotion recognition using deep learning, achieving robust results through effective data processing and augmentation. Future improvements could include:
- Extending support for male voices.
- Enhancing model accuracy with additional datasets and advanced techniques.

![Screenshot 2025-01-02 092155](https://github.com/user-attachments/assets/32500ccb-f4de-4c93-9013-ec04abf09ad4)

![Screenshot 2025-01-02 092139](https://github.com/user-attachments/assets/79dbd786-ea5c-46c2-86a9-496f00825d4a)
