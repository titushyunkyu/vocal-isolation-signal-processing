# Vocal Isolation with Signal Processing

## Overview

This project isolates vocals from a full song using digital signal processing techniques such as **spectral gating** and **harmonic-percussive source separation (HPSS)**. By analyzing the time-frequency structure of the audio, the system effectively suppresses background instrumentation while preserving vocal lines, creating a cleaner vocal-only track.

## Techniques Used

- **Spectral Gating**: Dynamically attenuates low-energy frequency bins to reduce ambient and instrumental noise.
- **Harmonic-Percussive Source Separation (HPSS)**: Separates audio into harmonic (vocals, synths) and percussive (drums, beats) components.
- **Short-Time Fourier Transform (STFT)**: Transforms the audio signal into the frequency domain for analysis and processing.

## Tools & Libraries

- Python (Jupyter Notebook)
- `librosa` – audio analysis and DSP
- `numpy`, `matplotlib`, `scipy`
- `soundfile` – audio read/write

## File Structure

```text
vocal-isolation-signal-processing/
│
├── Vocal_Isolation_With_Signal_Processing.ipynb    # Main notebook
├── audio_samples/
│   ├── original_track.wav                          # Input track
│   ├── vocals_isolated.wav                         # Output vocals
│   └── spectrograms/
│       ├── original_spectrogram.png
│       └── isolated_spectrogram.png
├── README.md                                        # This file
└── requirements.txt                                 # Python dependencies
```
## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/vocal-isolation-signal-processing.git
   cd vocal-isolation-signal-processing
2. Install the required libraries:
  ```bash
  pip install -r requirements.txt
  ```
3. Run the notebook:
```bash
jupyter notebook Vocal_Isolation_With_Signal_Processing.ipynb
```

## Video Presentation 🎬

Want to see how it works and what I learned?  
📺 [Watch the full video presentation on Google Drive](https://drive.google.com/file/d/1Cti0kwNsv1vOgR2w6rOlqAqHbvoHhKSw/view?usp=sharing)

## Sample Output

- 🎧 Original Audio: `audio_samples/original_track.wav`
- 🎤 Isolated Vocals: `audio_samples/vocals_isolated.wav`
- 📊 PCA/Spectrogram Visuals: `audio_samples/spectrograms/`

## File Structure

```text
vocal-isolation-signal-processing/
│
├── Vocal_Isolation_With_Signal_Processing.ipynb    # Main notebook
├── audio_samples/                                  # Auto-generated folder
│   ├── original_track.wav                          # Input (downloaded automatically)
│   ├── vocals_isolated.wav                         # Output vocals
│   └── spectrograms/
│       ├── original_spectrogram.png
│       └── isolated_spectrogram.png
├── README.md                                        # This file
└── requirements.txt                                 # Python dependencies
```

## Contributors

This project was developed in collaboration with:
- Matthew Batmunkh
- Gary Park
