# chroma-sense

# ChromaSense: Color Detection using KNN

ChromaSense is a machine learning-based project designed to detect and classify colors in images using the **K-Nearest Neighbors (KNN)** algorithm. It takes pixel input and predicts the closest color name from a labeled dataset of common colors.

---

## Features

- Detects color name from an image pixel.
- Uses KNN classifier for simplicity and performance.
- Easy to use via command-line or script.
- CSV-based color dataset for flexible training.

---

## Tech Stack

- Python
- OpenCV
- Pandas
- Scikit-learn (for KNN)

---

## Dataset

Uses a CSV file with the following format

You can expand it with as many labeled colors as needed.

---

## How It Works

1. Load the CSV dataset of named colors.
2. Train a **KNN classifier** using RGB values.
3. Read an image using OpenCV.
4. On mouse click, get the pixel RGB and predict the nearest color name.

---

##  How to Run

```bash
git clone https://github.com/yourusername/chromasense.git
cd chromasense
pip install -r requirements.txt
python chromasense.py


