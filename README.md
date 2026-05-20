# Celebrity Image Classification Using Machine Learning

This project is an image classification system built using Machine Learning and Computer Vision techniques.  
The model detects faces and classifies celebrity images using OpenCV, Haar Cascade, Wavelet Transform, and an SVM classifier.

---

## Features

- Face and eye detection using Haar Cascade
- Image preprocessing using Wavelet Transform
- Feature extraction from facial images
- Celebrity image classification using SVM
- Trained ML model saved using Joblib
- Simple and efficient prediction pipeline

---

## Technologies Used

- Python
- OpenCV (cv2)
- Haar Cascade Classifier
- PyWavelets
- NumPy
- Matplotlib
- Scikit-learn
- SVM (Support Vector Machine)
- Joblib

---

## Project Workflow

1. Collect celebrity image dataset
2. Detect faces and eyes using Haar Cascade
3. Crop facial regions
4. Apply Wavelet Transform for feature extraction
5. Combine raw image features and wavelet features
6. Train SVM classification model
7. Save trained model using Joblib
8. Predict celebrity from new images

---

## Folder Structure

```bash
project/
│
├── images_dataset/
├── cropped/
├── model/
├── server/
├── ui/
├── wavelet.py
├── train_model.ipynb
├── util.py
├── saved_model.pkl
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

### Train Model

```bash
python train_model.py
```

### Run Server

```bash
python server.py
```

---

## Example Libraries Used

```python
import cv2
import pywt
import numpy as np
from sklearn.svm import SVC
```

---

## Machine Learning Model

The classification model uses:

- Support Vector Machine (SVM)
- StandardScaler
- GridSearchCV for hyperparameter tuning

---

## Future Improvements

- Deep Learning based classification
- Real-time webcam prediction
- Better UI/UX
- Deploy model online
- Improve dataset size and accuracy

---

## Author

Jashandeep Singh

---

## License

This project is for educational and learning purposes.
