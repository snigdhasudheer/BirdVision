# 🐦 BirdVision AI – Deep Learning-Based Bird Species Identification

BirdVision AI is an intelligent bird species identification system that leverages Deep Learning and Computer Vision to classify bird images into 20 different species.

The project uses transfer learning with a pretrained ResNet-50 architecture implemented in PyTorch. It integrates Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize the important image regions influencing the model's predictions, making the classification process more interpretable.

**Key Features:**
- Identification of 20 different bird species.
- Deep learning-based classification using ResNet-50.
- Transfer learning and image data augmentation.
- Top-1 and Top-5 prediction results.
- Prediction confidence scores.
- Explainable AI using Grad-CAM heatmaps.
- Interactive web interface for image-based predictions.
- Model evaluation using accuracy, loss curves, and confusion matrices.

**Technology Stack:**
- Python, PyTorch, Torchvision
- ResNet-50, CNN, Transfer Learning
- OpenCV, NumPy, Pandas
- Grad-CAM, Matplotlib, Seaborn
- React.js, Vite
- FastAPI, SQLite

**Model Performance:**
- Top-1 Accuracy: 96%
- Top-5 Accuracy: 100%
- Number of Classes: 20

*Note: Evaluation was conducted on a test set of 100 images, so the reported accuracy is preliminary.*

**Objective:** To make bird species identification more accessible through AI while supporting biodiversity awareness and explainable machine learning.
