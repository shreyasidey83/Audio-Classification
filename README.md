# 🎧 Audio Classification using Deep Learning

An end-to-end Audio Classification project built using **Python, TensorFlow/Keras, Librosa, and Machine Learning** to automatically classify environmental sounds into different categories. The project demonstrates the complete deep learning pipeline, including data preprocessing, feature extraction, model training, evaluation, and prediction.

---

## 📌 Project Overview

Audio classification is an important application of Artificial Intelligence that enables computers to recognize and categorize sounds automatically. This project uses the **UrbanSound8K** dataset to train a deep learning model capable of identifying various urban environmental sounds.

The workflow includes:

- Audio preprocessing
- Feature extraction using MFCCs
- Data visualization
- Neural Network model training
- Model evaluation
- Prediction on unseen audio samples

---

## ✨ Features

- 🎵 Audio preprocessing with Librosa
- 📊 MFCC (Mel Frequency Cepstral Coefficients) feature extraction
- 📈 Training & validation visualization
- 🤖 Deep Learning model using TensorFlow/Keras
- 📉 Performance evaluation
- 🔍 Prediction on custom audio files
- 💾 Model saving and loading

---

## 📂 Dataset

This project uses the **UrbanSound8K** dataset.

**Dataset Link**

https://urbansounddataset.weebly.com/urbansound8k.html

or

https://www.kaggle.com/datasets/chrisfilo/urbansound8k

### Dataset Information

- **Total Audio Samples:** 8,732
- **Audio Length:** ≤ 4 seconds
- **Sampling Rate:** 44.1 kHz
- **Number of Classes:** 10

### Classes

| Class ID | Sound |
|-----------|----------------|
| 0 | Air Conditioner |
| 1 | Car Horn |
| 2 | Children Playing |
| 3 | Dog Bark |
| 4 | Drilling |
| 5 | Engine Idling |
| 6 | Gun Shot |
| 7 | Jackhammer |
| 8 | Siren |
| 9 | Street Music |

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Librosa
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Audio-Classification/
│
├── Audio_Classification.ipynb
├── requirements.txt
├── README.md
├── dataset/
├── saved_model/
├── images/
└── outputs/
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/shreyasidey83/Audio-Classification.git
```

Move into the project

```bash
cd Audio-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Audio_Classification.ipynb
```

---

## 🔄 Workflow

```
Audio Dataset
      │
      ▼
Load Audio Files
      │
      ▼
Preprocessing
      │
      ▼
MFCC Feature Extraction
      │
      ▼
Train-Test Split
      │
      ▼
Deep Learning Model
      │
      ▼
Training
      │
      ▼
Evaluation
      │
      ▼
Prediction
```

---

## 📊 Feature Extraction

The project uses **MFCC (Mel Frequency Cepstral Coefficients)**, one of the most widely used feature extraction techniques in audio signal processing.

MFCCs capture the timbral characteristics of audio signals and provide compact numerical representations suitable for machine learning and deep learning models.

---

## 🧠 Model

The model is implemented using **TensorFlow/Keras Sequential API**.

Typical architecture includes:

- Dense Layers
- ReLU Activation
- Dropout
- Softmax Output Layer

Loss Function

```
Categorical Crossentropy
```

Optimizer

```
Adam
```

Evaluation Metric

```
Accuracy
```

---

## 📈 Results

The trained model successfully learns to distinguish between different environmental sounds using extracted MFCC features.

Performance is evaluated using:

- Training Accuracy
- Validation Accuracy
- Loss Curves
- Test Accuracy

---

## 📷 Sample Visualizations

- Waveforms
- Spectrograms
- MFCC Heatmaps
- Training Accuracy Curve
- Validation Loss Curve

*(Add screenshots inside an `images/` folder and update this section if available.)*

---

## 🚀 Future Improvements

- CNN-based Audio Classification
- Transfer Learning
- Audio Data Augmentation
- Real-time Audio Prediction
- Web Application using Streamlit
- Mobile Deployment

---

## 📚 References

UrbanSound8K Dataset

https://urbansounddataset.weebly.com/urbansound8k.html

Librosa Documentation

https://librosa.org/

TensorFlow Documentation

https://www.tensorflow.org/

Scikit-learn Documentation

https://scikit-learn.org/

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👩‍💻 Author

**Shreyasi Dey**

B.Tech Computer Science & Engineering (AI & ML)

GitHub: https://github.com/shreyasidey83

LinkedIn: *(Add your LinkedIn profile here)*

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
