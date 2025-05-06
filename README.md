# music-genre-classification
# 🎵 GTZAN Music Genre Classification using Deep Learning

This project implements a deep learning model to classify music genres from audio features extracted from the GTZAN dataset. It uses features such as MFCCs, chroma, and spectral contrast to predict the genre of a music track.

## 📊 Dataset
- Source: [GTZAN Genre Collection](http://marsyas.info/downloads/datasets.html)
- 10 Genres: 
  - Blues, Classical, Country, Disco, HipHop, Jazz, Metal, Pop, Reggae, Rock
- Each audio clip is 30 seconds long.
- We used a `.csv` file with pre-extracted 3-second chunk features.

## 📌 Project Pipeline
1. **Data Loading**
2. **Preprocessing**: Null value check, label encoding, and feature scaling
3. **Model Building**: Deep neural network using TensorFlow/Keras
4. **Training**: Achieved validation accuracy of **92.4%**
5. **Evaluation**: Confusion matrix, classification report, accuracy/loss plots

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- Librosa (for audio processing)
- Pandas, NumPy
- Matplotlib, Seaborn (visualization)

## 📈 Results
- **Validation Accuracy**: 92.4%
- Confusion matrix and metrics confirm strong performance across most genres.

## 📁 Files
- `gtzan-genre-classification-deep-learning-val-92-4.ipynb`: Main notebook with all code and analysis.
- `features_3_sec.csv`: Input dataset (not included here due to size constraints).

## ✅ How to Run
1. Clone the repo
2. Install dependencies (`pip install -r requirements.txt`)
3. Run the notebook on Jupyter or Colab

## 🙌 Acknowledgements
- GTZAN Dataset creators
- TensorFlow & Librosa community

---

**Feel free to fork or star this repo if you find it useful!**
