# Emotion Detection CNN 😄😠😢

A deep learning project using Convolutional Neural Networks (CNN) to detect emotions from grayscale facial images.

## 📌 Features
- Trained on 48x48 pixel grayscale images
- Classifies into 7 emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
- Uses TensorFlow/Keras for model building
- Easily extendable to real-time emotion detection

## 🧠 Model Architecture
- CNN with multiple Conv2D and MaxPooling layers
- Dropout regularization
- Softmax activation for classification

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/rezasrk1/emotion-detection-cnn
cd emotion-detection-cnn

# Install requirements
pip install -r requirements.txt

# Train model
python src/train.py

# Predict emotion
python src/predict.py --image path/to/image.jpg



