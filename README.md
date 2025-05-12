

---

# 🎥 Multimodal Emotion Detection System

This project implements a **Multimodal Emotion Detection System** that analyzes both **facial expressions** and **audio features** from video input to detect emotional states. It combines **computer vision**, **audio signal processing**, and **rule-based classification** for robust emotion prediction.

---

## 🔍 Features

* 😐 **Facial Emotion Recognition** using DeepFace on sampled video frames
* 🔊 **Audio Emotion Recognition** using MFCC, ZCR, RMSE, and spectral features via **Librosa**
* 🔗 **Multimodal Fusion** to combine facial and vocal emotion insights
* 📊 **Interactive Visualizations** using matplotlib
* 🎞️ **Video upload support** in Google Colab for end-to-end execution

---

## 🧠 How It Works

1. 📥 **Upload a video** file via Google Colab
2. 🧑‍🦱 **Extract facial frames** and detect emotions using DeepFace
3. 🎧 **Extract and process audio** using spectral features (MFCC, ZCR, RMSE)
4. 🧠 **Classify audio emotion** using threshold-based logic
5. 🔄 **Fuse** both facial and audio emotion cues for a final prediction
6. 📈 **Visualize results** with bar charts and audio spectrograms

---

## 📁 Requirements

Make sure Python 3.x is installed and the following libraries are available:

```bash
pip install opencv-python librosa deepface moviepy matplotlib numpy
```

If running in **Google Colab**, also ensure:

```bash
pip install google-colab
```

### Additional Modules Used:

* `IPython.display` (for media output in Colab)

---

## 🚀 Getting Started

Run this project in **Google Colab** for best compatibility.

### Sample Usage:

```python
from your_script_name import MultimodalEmotionDetector

detector = MultimodalEmotionDetector()
detector.run_analysis()
```

> ⚠️ Note: DeepFace will download pre-trained models on the first run, which may take some time.

---

## 📊 Output

The system provides the following outputs:

* 🧠 **Dominant facial emotions** detected over video frames
* 🎧 **Classified audio emotion** from extracted speech features
* 🔄 **Final fused emotion** using combined audio-visual logic
* 📈 **Bar charts and spectrograms** for clear visualization of results

---

## 📌 Use Case

This system is ideal for use in:

* 🎓 Affective computing research
* 💻 Human-computer interaction studies
* 🧍 Behavioral analysis projects
* 🎥 Multimedia emotion analytics

---

## 📄 License

This project is provided for **educational and research purposes only**.
Please refer to the licenses of individual libraries (e.g., DeepFace, Librosa) for commercial usage terms.

---

