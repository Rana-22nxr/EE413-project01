# Speech Digit Classification using DSP

## Description
This project classifies spoken digits from the Free Spoken Digit Dataset (FSDD) using Digital Signal Processing techniques.

The project includes:
- Time-domain analysis
- Frequency-domain analysis using DFT
- STFT analysis
- Wavelet transform analysis
- Feature extraction
- Classification using machine learning models
- Performance comparison

---

## Team Members
- Sadeem Alsahli
- Jumana Alarfaji
- Rana Baagag
- Lena Almuhaizie

---

## Dataset
We used the Free Spoken Digit Dataset (FSDD), which contains audio recordings of spoken digits from 0 to 9.

---

## Methodology
1. Load dataset
2. Visualize waveforms
3. Apply preprocessing/filtering
4. Extract time-domain features
5. Extract DFT features
6. Extract STFT features
7. Extract wavelet features
8. Compare feature extraction methods
9. Train machine learning models
10. Compare model performance

---

## Features Extracted

### Time Domain Features
- Energy
- RMS Energy
- Zero Crossing Rate
- Envelope Mean
- Autocorrelation Peak

### DFT Features
- Peak Frequency
- Spectral Energy
- Spectral Centroid
- Bandwidth
- Spectral Rolloff
- Spectral Flatness

### STFT Features
- Mean STFT Energy
- STFT Variance
- Energy Change
- STFT Spectral Centroid
- STFT Bandwidth

### Wavelet Features
- Wavelet Energy
- Wavelet Entropy
- Statistical coefficients

---

## Feature Set Comparison (Using SVM)

| Feature Set | Accuracy |
|------------|------------|
| All Features | 82.67% |
| DFT | 61.17% |
| Wavelet | 52.17% |
| STFT | 50.83% |
| Time-domain | 39.67% |

---

## Model Comparison

| Model | Accuracy |
|--------|------------|
| SVM | 82.67% |
| Logistic Regression | 79.50% |
| KNN | 77.17% |

---

## Final Result
The best performance was achieved by combining all extracted features and using an SVM classifier.

Final Accuracy: **82.67%**

---

## How to Run
1. Download the FSDD dataset
2. Open the notebook in Google Colab or Jupyter Notebook
3. Install required libraries
4. Run all cells sequentially

---

## Required Libraries
- numpy
- pandas
- matplotlib
- librosa
- scikit-learn
- pywavelets
- scipy

---

## AI Assistance
ChatGPT was used only for permitted tasks such as debugging syntax issues, improving documentation, explaining programming concepts, and formatting visualizations.

All core DSP implementations, feature extraction methods, classification logic, and final analysis were completed, tested, and verified by the team.
