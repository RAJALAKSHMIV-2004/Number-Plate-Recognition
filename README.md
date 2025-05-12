# 🔍 Number Plate Recognition

A Python-based Automatic Number Plate Recognition (ANPR) system using OpenCV and Tesseract OCR. Built in Jupyter Notebook for quick experimentation and visualization.

## 📦 What's Inside

* 🧠 Image processing pipeline (grayscale, blur, edge detection)
* 🔳 Contour detection to locate number plates
* 🔤 OCR using Tesseract for text extraction
* 📸 Easy to test with your own images

## ⚙️ Setup

1. **Install dependencies**:

```bash
pip install opencv-python numpy matplotlib pytesseract
```

2. **Install Tesseract**:

* **Ubuntu**:

  ```bash
  sudo apt install tesseract-ocr
  ```
* **Windows/macOS**: [Tesseract install guide](https://github.com/tesseract-ocr/tesseract)

3. **Verify Tesseract**:

```bash
tesseract --version
```

## 🚀 Getting Started

* Open the notebook:

  ```bash
  jupyter notebook NumberPlateRecognition.ipynb
  ```
* Update the image path in the notebook to test your own files.
* Run all cells to see detection and OCR in action.

## 🖼️ Sample Workflow

1. Load image
2. Preprocess and detect contours
3. Extract number plate
4. Apply OCR → Get text

## 🔧 Customization

* Replace image paths with video stream (OpenCV `VideoCapture`)
* Fine-tune preprocessing thresholds for better detection
* Switch to a deep learning model (e.g., YOLO) for improved accuracy

## 📄 License

This project is licensed under the MIT License. 

