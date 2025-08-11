# 🐕 Dog Emotion Detection Dataset Training

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![YOLO](https://img.shields.io/badge/YOLO-v11-orange.svg)](https://github.com/ultralytics/ultralytics)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Dataset](https://img.shields.io/badge/Dataset-6335%20Images-brightgreen.svg)](https://drive.google.com/file/d/1TI3cvUWpjHNjQxfTAmTGQ8moxPrQFYPW/view?usp=sharing)

A comprehensive machine learning project for detecting and classifying dog emotions using state-of-the-art YOLOv11 architecture. This project provides a complete pipeline from dataset preparation to model training and evaluation.

## 🎯 Overview

Understanding canine emotions through facial expressions and body language is crucial for pet owners, trainers, and veterinary professionals. This project addresses this challenge by developing an AI-driven system that automatically detects and classifies five distinct dog emotional states:

- 😊 **Happy** - Joyful and content expressions
- 🚨 **Alert** - Attentive and focused behavior
- 😔 **Frown** - Sad or concerned expressions
- 😌 **Relax** - Calm and peaceful demeanor
- 😠 **Angry** - Aggressive or defensive behavior

## ✨ Features

- **Advanced Architecture**: Built on YOLOv11 (Ultralytics) for real-time object detection
- **Comprehensive Dataset**: 6,335 carefully annotated images with 5 emotion classes
- **Data Augmentation**: Robust preprocessing with rotation, cropping, brightness adjustment, and noise injection
- **Professional Pipeline**: Complete workflow from data preparation to model evaluation
- **Easy Deployment**: Ready-to-use notebooks for training, testing, and inference
- **Performance Metrics**: Comprehensive evaluation with confusion matrices and performance curves

## 📊 Dataset

### Dataset Statistics
- **Total Images**: 6,335
- **Classes**: 5 dog emotions
- **Format**: YOLOv11 compatible annotations
- **Input Size**: 320x320 pixels
- **Split**: 70% train, 20% validation, 10% test

### Data Augmentation
The dataset includes 5 augmented versions of each source image with:
- Random cropping (0-29%)
- Random rotation (±20°)
- Random shear (±15° horizontal, ±14° vertical)
- Brightness adjustment (±24%)
- Gaussian blur (0-2 pixels)
- Salt and pepper noise (1.64% of pixels)

### Access
📥 **Download Dataset**: [Google Drive Link](https://drive.google.com/file/d/1TI3cvUWpjHNjQxfTAmTGQ8moxPrQFYPW/view?usp=sharing)

## 🧠 Model Architecture

| Component | Specification |
|-----------|---------------|
| **Framework** | YOLOv11 (Ultralytics) |
| **Backend** | PyTorch ≥2.0 |
| **Input Resolution** | 320×320 |
| **Annotation Format** | YOLOv5-compatible (.txt) |
| **Training Tool** | Roboflow |
| **Optimization** | Transfer learning with pre-trained weights |

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- CUDA-compatible GPU (recommended for training)
- Git

### Setup
```bash
# Clone the repository
git clone https://github.com/Abhijeet999-beep/Dog-Emotion-Detection-Dataset-Training.git
cd Dog-Emotion-Detection-Dataset-Training

# Install dependencies
pip install -r requirements.txt
```

### Dependencies
```
ultralytics>=8.0.20        # YOLOv11 framework
opencv-python              # Image/video processing
matplotlib                 # Visualization and plotting
numpy                      # Numerical operations
PyYAML                     # Configuration file handling
torch>=2.0                 # PyTorch backend
```

## 📖 Usage

### Training
```python
# Open training notebook
jupyter notebook jupyter_notebooks/training.ipynb
```

### Testing on Images
```python
# Test on single or multiple images
jupyter notebook jupyter_notebooks/testing_images.ipynb
```

### Testing on Video
```python
# Process video files
jupyter notebook jupyter_notebooks/testing_video.ipynb
```

### Two-Stage Pipeline
```python
# Advanced pipeline with preprocessing
jupyter notebook jupyter_notebooks/Two-Stage Model Pipeline.ipynb
```

## 📁 Project Structure

```
Dog-Emotion-Detection-Dataset-Training/
├── 📁 jupyter_notebooks/          # Jupyter notebooks for training and testing
│   ├── training.ipynb             # Main training pipeline
│   ├── testing_images.ipynb       # Image inference and evaluation
│   ├── testing_video.ipynb        # Video processing capabilities
│   └── Two-Stage Model Pipeline.ipynb  # Advanced preprocessing pipeline
├── 📁 runs/                       # Training outputs and results
│   ├── 📁 train/                  # Training artifacts
│   │   ├── 📁 weights/            # Trained model weights
│   │   ├── confusion_matrix.png   # Classification performance
│   │   ├── results.csv            # Training metrics
│   │   └── ...                    # Additional evaluation plots
│   └── 📁 detect/                 # Detection results
├── requirements.txt                # Python dependencies
├── README.md                      # This file
└── README.roboflow.txt            # Dataset documentation
```

## 📈 Results

The trained model provides comprehensive evaluation metrics including:
- **Confusion Matrix**: Class-wise classification accuracy
- **Precision-Recall Curves**: Performance across different thresholds
- **F1 Score**: Balanced measure of precision and recall
- **ROC Curves**: Model discrimination ability
- **Training Metrics**: Loss curves and validation performance

## 🔮 Future Scope

- **Real-time Deployment**: Mobile and edge device optimization
- **Behavioral Monitoring**: Integration with pet owner applications
- **Cross-species Detection**: Generalization to other animals
- **Voice Translation**: Emotion-to-speech synthesis systems
- **API Development**: RESTful service for easy integration

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues, feature requests, or pull requests.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Abhijeet** - [GitHub Profile](https://github.com/Abhijeet999-beep)

## 📞 Contact

- **GitHub**: [@Abhijeet999-beep](https://github.com/Abhijeet999-beep)
- **Project Link**: [https://github.com/Abhijeet999-beep/Dog-Emotion-Detection-Dataset-Training](https://github.com/Abhijeet999-beep/Dog-Emotion-Detection-Dataset-Training)

## 🙏 Acknowledgments

- **Ultralytics** for the YOLOv11 framework
- **Roboflow** for dataset annotation and management tools
- **OpenCV** for computer vision capabilities
- **PyTorch** for deep learning backend

---

⭐ **If this project helps you, please give it a star!** ⭐

---

*Built with ❤️ for the AI and pet care communities* 

