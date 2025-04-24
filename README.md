# 👶 Crybaby - Baby Cry Sound Visualizer

**Crybaby** is a sound analysis project that demonstrates the ability to detect and visualize the spectrogram of a baby's crying audio. It processes a sample `.wav` file, removes background noise, trims silence, and then converts the audio to a mel-spectrogram for analysis and visualization.

---

## 🔧 Features

- 🔊 Downloads a baby cry sound from Google Drive
- 🧹 Performs background noise reduction using `noisereduce`
- ✂️ Trims silent parts of the audio using `librosa.effects.trim`
- 📊 Generates a clean mel-spectrogram using `librosa`
- 📈 Visualizes the spectrogram using `matplotlib`

---

## 📦 Requirements

Install the necessary packages using pip:

```bash
pip install noisereduce gdown librosa matplotlib numpy
