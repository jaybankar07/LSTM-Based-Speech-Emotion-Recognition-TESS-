# LSTM-Based-Speech-Emotion-Recognition-TESS-
An LSTM-based deep learning model for speech emotion recognition using the TESS (Toronto Emotional Speech Set) dataset, including audio preprocessing, MFCC feature extraction, training, and evaluation.

# LSTM-Based Speech Emotion Recognition (TESS)

This repository presents an implementation of a Deep Learning model using **Long Short-Term Memory (LSTM)** networks for **Speech Emotion Recognition** on the **TESS (Toronto Emotional Speech Set)** dataset.

The project demonstrates an end-to-end pipeline, starting from audio preprocessing and feature extraction to model training and evaluation.

---

## 🔍 Project Highlights

- Used **TESS (Toronto Emotional Speech Set)** dataset  
- Extracted **MFCC features** from audio using **librosa**
- Trained an **LSTM neural network** using **TensorFlow / Keras**
- Performed **data preprocessing, label encoding, and padding**
- Evaluated the model using accuracy, classification report, and confusion matrix
- Visualized training and validation performance

---

## Toronto emotional speech set (TESS)

- It is a voice-based dataset which content human emotions. All the voice available in this dataset are of female’s, there are two categories first one is of Old Female Voice (OAF) & second one is of Young Female Voice (YAF).
Data Set: 
o	OAF_Fear
o	OAF_Pleasant_surprise
o	OAF_Sad
o	OAF_angry
o	OAF_disgust
o	OAF_happy
o	OAF_neutral
o	YAF_angry
o	YAF_disgust
o	YAF_fear
o	YAF_happy
o	YAF_neutral
o	YAF_pleasant_surprised
o	YAF_sad

OAF: Older Adult Female
YAF: Younger Adult Female 

- The Common Sentence in all the voice is “Say the word …….”, and all audios are of almost same range 1 to 2 sec.
- Model: LSTM (Long Short-Term Memory)

> ⚠️ The TESS dataset is not included in this repository due to size limitations.  
> Please download it separately and place it inside the `data/` folder.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Librosa
- NumPy
- Pandas
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository

git clone <your-repo-url>
cd tess-lstm-speech-emotion-recognition

---

## 📈 Future Improvements

- Add more datasets (RAVDESS, CREMA-D, SAVEE)
- Use Bidirectional LSTM / GRU
- Convert to real-time emotion detection
- Add model saving & inference script

---

## 👨‍💻 Author

Jay Bankar
(Deep Learning / AI Enthusiast)

