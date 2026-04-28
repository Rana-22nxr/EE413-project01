# Speech Digit Classification using DSP

## Description
This project classifies spoken digits from the Free Spoken Digit Dataset (FSDD) using Digital Signal Processing (DSP) techniques.

The implemented analysis methods include:
- Time-domain analysis
- DFT-based frequency-domain analysis
- STFT time-frequency analysis
- Wavelet transform analysis

## Team Members
- Sadeem Alshaly
- Jumana Alarfaji
- Rana Baagag
- Lena Almuhaizie

## Dataset
The project uses the Free Spoken Digit Dataset (FSDD), which contains WAV recordings of spoken digits from 0 to 9.

## Methodology
The project follows these main steps:
1. Load and verify the dataset
2. Visualize speech waveforms
3. Apply basic filtering
4. Extract signal envelope
5. Extract time-domain features
6. Extract DFT-based frequency features
7. Extract STFT-based features
8. Extract wavelet-based features
9. Combine all features
10. Train and evaluate machine learning classifiers

## Features Extracted

### Time-Domain Features
- Energy
- RMS
- Zero-crossing rate
- Signal duration
- Envelope statistics

### DFT Features
- Spectral centroid
- Spectral bandwidth
- Dominant frequency
- Spectral energy

### STFT Features
- Mean STFT energy
- Variance of STFT energy
- Mean spectral centroid over frames
- Mean spectral bandwidth over frames

### Wavelet Features
- Wavelet energy
- Wavelet entropy
- Statistical features of wavelet coefficients

## Machine Learning Models
The following classifiers were tested:
- SVM
- KNN
- Logistic Regression

## Results
The best-performing model was:

| Model | Accuracy |
|---|---|
| SVM | 82.67% |
| Logistic Regression | 79.50% |
| KNN | 77.17% |

Feature set comparison:

| Feature Set | Accuracy |
|---|---|
| All Features | 79.50% |
| Wavelet | 61.83% |
| DFT | 48.67% |
| STFT | 36.50% |
| Time-domain | 29.50% |

## Conclusion
Combining features from multiple DSP domains improved the classification performance compared to using only one feature type. The SVM classifier achieved the highest accuracy, showing that the combined DSP features provide useful information for spoken digit classification.

## How to Run
1. Download the Free Spoken Digit Dataset (FSDD).
2. Open the notebook `Project(1)_EE413_(.ipynb` in Google Colab or Jupyter Notebook.
3. Install the required libraries.
4. Run all cells sequentially.

## Required Libraries
```txt
numpy
pandas
matplotlib
librosa
scikit-learn
pywavelets
scipy
