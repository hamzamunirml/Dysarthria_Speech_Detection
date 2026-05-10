# 🗣️ Dysarthria Speech Detection using Deep Learning

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/fa9c2c37-3ab6-4407-884c-3c8925e7c06b" />


##  Project Overview
This project focuses on detecting Dysarthric Speech using Deep Learning and Speech Processing techniques. The model is trained on speech audio recordings and classifies whether the speech belongs to a Dysarthric speaker or a Normal (Control) speaker.

The project was developed in Python using Google Colab and includes audio preprocessing, feature extraction, model training, evaluation, and Flask-based deployment.

---

##  Dataset Information
The dataset contains `.wav` speech recordings categorized into the following classes:

- Female Control Speakers (`F_Con`)
- Male Control Speakers (`M_Con`)
- Female Dysarthric Speakers (`F_Dys`)
- Male Dysarthric Speakers (`M_Dys`)

###  Target Labels
- `0` → Control Speech
- `1` → Dysarthric Speech

---

##  Objective
To build an AI-based speech classification model capable of automatically detecting Dysarthria from speech audio samples.

---

##  Data Preprocessing
The following preprocessing steps were applied:

- Audio loading using Librosa
- Noise handling and audio normalization
- Feature extraction from speech signals
- Feature scaling using StandardScaler
- Dataset balancing using SMOTE
- Train/Test data splitting

---

##  Audio Features Extracted
The following speech features were extracted from audio files:

- MFCC (Mel Frequency Cepstral Coefficients)
- Chroma Features
- Spectral Features
- RMS Energy
- Zero Crossing Rate

---

##  Exploratory Data Analysis (EDA)
The following visualizations and analyses were performed:

- Class distribution graphs
- Audio waveform visualization
- Feature distribution plots
- Correlation analysis
- Training vs Validation accuracy/loss graphs

📁 Graphs and plots are stored in the `graphs/` folder.


---

## 🤖 Deep Learning Model Used
The project uses a Neural Network model built with TensorFlow/Keras.

###  Model Architecture
- Dense Layer
- ReLU Activation
- Dropout Layers
- Sigmoid Output Layer

###  Training Techniques
- EarlyStopping Callback
- Validation Monitoring
- Binary Classification

---

## 📊 Model Evaluation Metrics
The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

## 🏆 Results
- Best Model: Deep Neural Network (DNN)
- High Accuracy achieved for Dysarthria detection
- Effective classification between Normal and Dysarthric speech
---

## ⚙️ Technologies Used
- Python
- Flask
- TensorFlow / Keras
- Librosa
- NumPy
- Scikit-learn
- Google Colab
- Ngrok

## 🚀 Google Colab Deployment
The Flask application is executed inside Google Colab and exposed to the internet using **Ngrok**.

### Workflow
1. Train the model in Google Colab
2. Save trained model and scaler
3. Run Flask GUI code
4. Start local Flask server
5. Generate public Ngrok URL
6. Open GUI in browser

   
## 👨‍💻 Author
**hamzamunirml**  

## Support ⭐
If you like it then give a ⭐
