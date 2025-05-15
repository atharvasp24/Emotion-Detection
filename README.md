
# Emotion Detection 🎭

A real-time facial emotion detection system using Convolutional Neural Networks (CNNs) with **MobileNetV2** as the base model and OpenCV for face detection and live predictions.

## 📂 Project Structure

```
Emotion-Detection/
│
├── train/                           # Folder with images categorized into 7 emotion classes
├── Model.h5                         # Trained emotion classification model
├── Face_Emotion_Detection.ipynb     # Jupyter Notebook with model training and inference logic
├── test_image.jpg                   # Sample image for testing emotion detection
├── haarcascade_frontalface_default.xml  # Haarcascade file for face detection
└── README.md                        # Project documentation
```

## 📋 Emotion Categories

- Angry
- Disgusted
- Fearful
- Happy
- Neutral
- Sad
- Surprised

## 🛠️ Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/atharvasp24/Emotion-Detection.git
   cd Emotion-Detection
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` is missing, install manually:
   ```bash
   pip install tensorflow opencv-python numpy matplotlib
   ```

3. **Run the notebook**
   Launch Jupyter and open `Face_Emotion_Detection.ipynb`.

## 🚀 How It Works

- Loads and preprocesses images from the `train/` folder.
- Trains a CNN model using transfer learning from MobileNetV2.
- Detects face using Haarcascade from a webcam or static image.
- Classifies emotion and displays it in real time.

## 📷 Demo

> Real-time emotion prediction with bounding box and label overlay on detected face.

## ✍️ Author

**Atharva Patil**  
📧 atharvasp24@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/atharva-patil)
