# LSTM with Fourier Analysis for Time Series Prediction

This project explores the combination of Long Short-Term Memory (LSTM) networks with frequency analysis to enhance the accuracy of time series predictions. Time series data, commonly used in finance, weather forecasting, and signal processing, often includes cyclical patterns. While LSTM networks are effective at capturing long-term dependencies, they may miss such periodic trends.

## Objective

The primary aim of this project is to evaluate whether integrating frequency-domain information with LSTM architectures can improve predictive performance on time series data, particularly when the data exhibits recurring patterns. This approach leverages Fourier-transformed components, attention mechanisms, and frequency selection strategies.

## Approach

1. **Data Preparation**: Synthetic datasets with trends, noise, and periodic components are generated to test the models.
2. **Model Architecture**: The study evaluates LSTM and BiLSTM architectures with Fourier transformations, focusing on common signal patterns within the frequency domain.
3. **Attention Mechanisms**: Different attention mechanisms are applied to the frequency components to capture relevant patterns more effectively.

## Google Colab

To run this project in Google Colab, access the notebook using the link below:

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wVBg6Yur82Wul8R7HsNVsnjG3V63poOh?usp=sharing)


## Results

Through empirical comparisons with baseline LSTM models, this project assesses under what conditions the integration of frequency analysis improves time series forecasting. Results indicate promising gains in accuracy for signals with recurring patterns, providing insights for further research in signal-specific optimizations.

---

This README provides an overview of the project, including objectives, methodology, and a link to run the notebook in Google Colab. Let me know if you’d like to add more sections or additional details!
