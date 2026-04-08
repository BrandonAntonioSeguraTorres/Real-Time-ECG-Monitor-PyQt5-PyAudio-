# 🫀 Real-Time ECG Monitor

A real-time electrocardiogram (ECG) monitoring application built in Python using **PyQt5**, **PyAudio**, and **pyqtgraph**.

This tool captures analog signals from an audio input (microphone or line-in), processes them using FFT-based filtering, and visualizes them in real time with an interactive GUI.

---

## 🚀 Features

* Real-time ECG signal acquisition from sound card
* FFT-based low-pass filtering (noise reduction)
* Signal inversion and auto-scaling
* Live visualization with high refresh rate
* Pause/resume monitoring
* Export high-resolution ECG plots (PNG)
* Record ECG signals to WAV (16-bit PCM)
* Load and visualize recorded WAV files
* Playback ECG signals in real-time simulation
* Interactive slider for signal navigation

---

## 🧠 How It Works

The application uses your computer's sound card as an analog-to-digital converter. Incoming signals are:

1. Captured via PyAudio
2. Processed using FFT filtering
3. Displayed in real time using pyqtgraph

This makes it ideal for **low-cost ECG setups and educational experiments**.

---

## 📦 Requirements

Install dependencies with:

```bash
pip install pyqt5 pyqtgraph pyaudio numpy scipy
```

---

## ▶️ Usage

Run the application:

```bash
python ecg_monitor.py
```

1. Select an input device
2. Start live monitoring
3. Adjust filtering and scaling
4. Record or export signals

---

## ⚠️ Disclaimer

This software is intended for **educational and experimental purposes only**.
It is **not a certified medical device** and should not be used for clinical diagnosis.

---

## 📌 Future Improvements

* PyQt6 migration
* Better digital filtering (bandpass ECG)
* Multi-channel support
* Integration with external hardware (e.g., ESP32, Brewscopio)

---

## 👨‍🔬 Author

Developed by **Antonio Van Gritte**
📧 [antoniovangritte@gmail.com](mailto:antoniovangritte@gmail.com)

---

## 📄 License

MIT License
