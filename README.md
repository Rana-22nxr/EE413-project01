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

## Team Members
- Sadeem Alsahli
- Jumana Alarfaji
- Rana Baagag
- Lena Almuhaizie

## Dataset
We used the Free Spoken Digit Dataset (FSDD), which contains audio recordings of spoken digits from 0 to 9.

## Methodology
1. Load dataset
2. Visualize waveforms
3. Apply preprocessing/filtering
4. Extract time-domain features
5. Extract DFT features
6. Extract STFT features
7. Extract wavelet features
8. Train machine learning models
9. Compare performance

## Features Extracted

### Time Domain
- Energy
- RMS
- Zero Crossing Rate
- Signal Duration

### DFT Features
- Spectral Centroid
- Spectral Bandwidth
- Dominant Frequency
- Spectral Energy

### STFT Features
- Mean STFT Energy
- STFT Variance

### Wavelet Features
- Wavelet Energy
- Wavelet Entropy

## Models Used
- KNN
- SVM
- Logistic Regression

## Results

| Model | Accuracy |
|--------|------------|
| SVM | 82.67% |
| Logistic Regression | 79.50% |
| KNN | 77.17% |

## Conclusion
Combining multiple DSP feature extraction methods improved classification performance. SVM achieved the highest accuracy.

## How to Run
1. Download FSDD dataset
2. Open notebook in Google Colab or Jupyter
3. Install required libraries
4. Run all cells

## AI Assistance
ChatGPT was used to assist with debugging, explaining DSP concepts, improving documentation, and reviewing code structure. All coding, testing, and final analysis were completed by the team.
