# Audio-Noise-Reduction-System-Using-FFT
This project delves in the real life application of FFT (Fast Fourier Transform) to filter out noise from audio signals


# Description
  
This Python script simulates a noise reduction system for audio signals. It generates a clean signal with multiple frequencies, adds white noise to create a noisy signal, and then attempts to remove the noise using a Power Spectral Density (PSD) based approach.

# Functionalities

Signal Generation: Creates a clean audio signal with a combination of sine waves at various frequencies.
Noise Addition: Introduces white noise to the clean signal to simulate a noisy audio scenario.
Noise Reduction:
    Calculates the Power Spectral Density (PSD) of the noisy signal to identify frequencies with high noise power.
    Filters out the high noise power frequencies from the PSD.
    Applies the filtered PSD back to the signal in the frequency domain using the Inverse Fast Fourier Transform (IFFT).
Audio Playback: Allows playback of the clean, noisy, and noise-reduced signals for comparison.
Visualization: Plots the clean, noisy, and noise-reduced signals in both the time and frequency domains.

# Usage

Open the script directly on google collab with the provided link and fire away.
The script will generate the clean, noisy, and noise-reduced signals and display plots for comparison.
You can listen to the audio signals using the provided playback functionality (available only in Jupyter Notebook or Google Colab).

# Additional Notes

This is a basic implementation of noise reduction using PSD (Power Spectral Density). More sophisticated techniques may achieve better results depending on the specific noise characteristics.
The script uses a threshold-based approach to filter noise in the PSD. The threshold value (150 in the code) might need adjustments based on the specific noise level in your audio signal.
