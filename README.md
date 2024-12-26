

# Emotion Detection Using Deep Learning  

This repository contains a deep learning-based application for **real-time emotion detection** from facial expressions. The model utilizes advanced CNN architectures like **VGG16** and hybrid models combining **VGG16** and **ResNet50** to achieve high accuracy in emotion classification.

## Features  
- **Emotion Classification**: Detects emotions such as happiness, sadness, anger, surprise, fear, and more.  
- **Real-Time Detection**: Supports live input via camera or uploaded images for instant emotion analysis.  
- **Hybrid Model**: Combines the strengths of VGG16 and ResNet50 for improved accuracy and efficiency.  

## How It Works  
1. **Image Input**: Upload a facial image or provide live input through a camera.  
2. **Preprocessing**: The image is processed and resized for compatibility with the model.  
3. **Feature Extraction**: The model extracts facial features using CNN architectures.  
4. **Emotion Prediction**: Classifies the input into predefined emotion categories.  
5. **Output**: Displays the detected emotion with confidence scores.  

## Requirements  
- Python 3.8+  
- Libraries:  
  - `tensorflow`  
  - `keras`  
  - `opencv-python`  
  - `numpy`  
  - `matplotlib`  

## Setup Instructions  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/janakiram180/Emotion-Detection.git  
   cd Emotion-Detection  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Download the pretrained model weights:  
   - Add the model weights to the appropriate directory (details provided in the repository).  

4. Run the application:  
   ```bash  
   python app.py  
   ```  

## Usage  
- **Image Upload**: Upload a facial image for analysis.  
- **Live Detection**: Use a connected camera to detect emotions in real time.  
- View the predicted emotion and corresponding confidence score on the interface.  

## Technologies Used  
- **TensorFlow/Keras**: For model training and implementation.  
- **VGG16 and ResNet50**: CNN architectures used for feature extraction and emotion classification.  
- **OpenCV**: For image processing and live camera input handling.  

## Dataset  
The model is trained on publicly available datasets containing diverse facial images annotated with emotion labels.  

## Future Enhancements  
- Add support for multi-emotion detection in group images.  
- Optimize the model for deployment on mobile and edge devices.  
- Enhance robustness for detecting subtle emotions.  

## License  
This project is licensed under the MIT License. See the `LICENSE` file for more details.  

