# 🚗 License Plate Detection and OCR using OpenCV & PyTesseract

Automatic License Plate Detection and OCR using OpenCV and PyTesseract. Detects vehicle license plates from images and extracts the license number using image processing and Optical Character Recognition (OCR).

---

## 📖 Overview

This project implements an **Automatic License Plate Recognition (ALPR)** system using image processing techniques and Optical Character Recognition (OCR).

The application first locates the license plate in a vehicle image using contour detection and then extracts the license plate number using **PyTesseract**.

---

## ✨ Features

- Detect vehicle license plates from images
- Image preprocessing for better accuracy
- Grayscale conversion
- Noise reduction using Bilateral Filtering
- Edge detection using Canny
- Contour detection to locate license plates
- Extract license plate text using Tesseract OCR
- Display detected license plate
- Save the final output image

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Imutils
- PyTesseract
- Jupyter Notebook

---

## 📂 Project Structure

```
License-Plate-Detection-OCR/
│
├── images/
│   ├── input.jpg
│   └── detected_license_plate.jpg
│
├── pytessarct.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/manasranjanmeher99/License-Plate-Detection-OCR.git

cd License-Plate-Detection-OCR
```

### 2. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 🔧 Install Tesseract OCR

Download and install **Tesseract OCR**.

### Windows

https://github.com/UB-Mannheim/tesseract/wiki

After installation, specify the Tesseract path:

```python
pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"
```

---

## ▶️ Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
pytessarct.ipynb
```

Run all cells.

---

## 🔄 Workflow

```
Input Vehicle Image
        │
        ▼
Resize Image
        │
        ▼
Convert to Grayscale
        │
        ▼
Apply Bilateral Filter
        │
        ▼
Canny Edge Detection
        │
        ▼
Find Contours
        │
        ▼
Locate License Plate
        │
        ▼
Crop Plate Region
        │
        ▼
Extract Text using OCR
        │
        ▼
Display & Save Results
```

---

## 📸 Sample Output

### Input Image


![Input Image](images/input.jpg)


### Detected License Plate


![Detected License Plate](images/detected_license_plate.jpg)


### OCR Result

```
MH20EE7602
```


---

## 📦 Requirements

- Python 3.8+
- OpenCV
- NumPy
- Imutils
- PyTesseract
- Jupyter Notebook

Install using:

```bash
pip install -r requirements.txt
```

---

## 🚀 Future Improvements

- Real-time license plate detection using webcam
- Video-based license plate recognition
- YOLO-based license plate detection
- Deep learning-based OCR
- Multiple license plate detection
- Automatic vehicle information lookup

---

## 👨‍💻 Author

**Manas Ranjan Meher**

---

## ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub.

---
