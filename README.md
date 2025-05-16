# Audio Signal Enhancement for Noisy Environments: Spectral Subtraction Approach

This project implements the **Spectral Subtraction** technique to reduce background noise from audio signals. It focuses on enhancing speech quality in noisy environments using classical signal processing methods. The system supports waveform input, STFT processing, noise estimation, subtraction in the spectral domain, and waveform reconstruction.

---

## 🎯 Objective

To improve the quality and intelligibility of speech signals captured in noisy environments using spectral subtraction, a well-established denoising technique in the frequency domain.

---

## 🧠 Key Features

- ✅ Load noisy speech audio files (WAV)
- ✅ Apply Short-Time Fourier Transform (STFT)
- ✅ Estimate and subtract noise spectrum
- ✅ Reconstruct clean signal using inverse STFT
- ✅ Visualize waveform and spectrogram before/after enhancement
- ✅ Evaluate using SNR (Signal-to-Noise Ratio)

---

## 🔧 Techniques Used

### Spectral Subtraction
1. Convert time-domain audio to frequency domain (STFT).
2. Estimate noise magnitude spectrum from silent regions.
3. Subtract estimated noise from each frame.
4. Retain phase and reconstruct using inverse STFT (ISTFT).
