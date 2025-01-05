# AI-Enhanced Emotion Insights for Billboard Advertising Success
This repository hosts my Master's project, AI-Enhanced Emotion Insights for Billboard Advertising Success, utilizing deep learning models (VGG16, ResNet50V2, MobileNet) and the FER-2013 dataset. It detects seven emotions in real-time with OpenCV, offering actionable insights to optimize billboard advertisements through AI-driven emotion analysis.

# Features
- Emotion Detection: Identifies seven emotions: happy, sad, angry, disgust, neutral, fear, and surprise.
- Pretrained Models: Implements VGG16, ResNet50V2, and MobileNet for emotion detection.
- Real-Time Analysis: Uses OpenCV for real-time image processing and emotion recognition.
- Data Insights: Provides confusion matrices, ROC curves, and other visualizations to evaluate model performance.

# Dataset
The project uses the FER-2013 dataset, which contains 36,000+ labeled facial images for training and validation. The dataset is downloaded using the Kaggle API.

## How to Run
1. Open the `VGG16_Model.ipynb` notebook.
2. Follow the steps outlined in the notebook for:
   - Data preprocessing (including automatic dataset download if `kaggle.json` is present)
   - Model training and evaluation
   - Generating insights through confusion matrices, accuracy/loss plots, and ROC curves
3. For real-time emotion detection, upload an image using the OpenCV implementation provided.

## Results
The project achieved:
- VGG16: 79.83% training accuracy and 57.57% validation accuracy.
- ResNet50V2: Comparable performance but slower convergence.
- MobileNet: Lightweight and faster, with moderate accuracy.

Sample outputs include:
- Accuracy/loss plots for training and validation
- Confusion matrices for different datasets
- Real-time emotion detection via OpenCV

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
