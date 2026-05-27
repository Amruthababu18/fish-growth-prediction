# 🐟 Fish Growth Analysis & Mass Prediction

A deep learning-based system for **fish species classification** and **automated mass/weight prediction** using image and measurement data. Built to support sustainable aquaculture by providing accurate growth insights and automating fish weight estimation for efficient monitoring.

---

## ✨ Features

- 🐠 Fish species classification from images using YOLOv8
-  📏 Fish length estimation using FastSAM segmentation
- ⚖️ Automated fish mass/weight prediction from image data
- 📊 Growth analysis and monitoring for aquaculture
- 🌐 Web-based interface for easy use (Flask)

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| Language | Python 3.x |
| Deep Learning | Keras, TensorFlow |
| Object Detection | YOLOv8 (Ultralytics) |
| Segmentation | FastSAM |
| Web Framework | Flask |
| Database | SQLite |
| Data Processing | Pandas, NumPy |

---

## 📁 Project Structure

```
fish-growth-prediction/
├── app.py                          # Main Flask application
├── app_file.py                     # App logic and routes
├── model_loader.py                 # Model loading utilities
├── models.py                       # Model architecture
├── length_estimator.py             # Fish length estimation logic
├── data_manager.py                 # Data handling and processing
├── requirements.txt                # Required Python libraries
└── static/                         # CSS, JS, UI assets
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/fish-growth-prediction.git
cd fish-growth-prediction
```

### 2. Install required libraries
```bash
pip install -r requirements.txt
```

### 3. Download model weights
The trained model weights are not included in this repo due to file size.
Download them and place in the project root folder:

| File | Download |
|------|----------|
| `final_weight_classification.h5` | [Google Drive Link](YOUR-GOOGLE-DRIVE-LINK) |
| `yolov8s-world.pt` | [Ultralytics Official](https://github.com/ultralytics/ultralytics) |
| `FastSAM-s.pt` | [FastSAM Official](https://github.com/CASIA-IVA-Lab/FastSAM) |

### 4. Run the application
```bash
python app.py
```
Open your browser and go to `http://localhost:5000`

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Overall Accuracy | _96.8%_ |
| Precision (Macro)  | _ 96.7%_ |
| Recall (Macro) | _96.8%_ |

---

## 📷 Screenshots

_Add screenshots of your web interface here_

---

## 🔬 Research Paper

This project was presented as a research paper:

**"Survey on Fish Growth Analysis and Fish Mass Prediction Using Deep Learning"**
Presented at **ICSTS 2025** — LBS Institute of Technology for Women, Trivandrum.

---

## 👩‍💻 Author

**Amrutha**
B.Tech Computer Science & Engineering

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/amruthababu2318)

---

## 📦 Dataset

The fish growth dataset used for training is available here:
[Google Drive / Kaggle Link](YOUR-DATASET-LINK)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
