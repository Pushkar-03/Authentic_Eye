# 👁️ Authentic_Eye — Face-Swapped Deepfake Detection

Authentic_Eye is a deep learning-based system designed to detect **face-swapped deepfake videos** using advanced computer vision and neural networks. It processes video frames, detects manipulated faces, and classifies content as real or fake with high accuracy.

This project is built using **TensorFlow/Keras** for model training and **Flask** for a user-friendly web interface. It’s intended for use in **digital forensics**, **AI ethics**, **media verification**, and **cybersecurity** applications.

---

## 🚀 Features

- 🎞️ **Video Frame Extraction** — Extracts frames from uploaded videos.
- 🧍 **Face Detection & Cropping** — Uses face detection (e.g., MTCNN, OpenCV) to focus on facial regions.
- 🧪 **Data Preprocessing & Augmentation** — Enhances model robustness using real/fake datasets.
- 🧠 **Deep Learning Model** — Trained with architectures like **Xception**, **ResNet**, or custom CNN.
- 📈 **Training & Evaluation** — Monitors accuracy, loss curves, and confusion matrices.
- 🌐 **Flask Web App** — Allows users to upload videos and receive deepfake analysis results in real-time.

---

## 📁 Project Structure


---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Authentic_Eye.git
cd Authentic_Eye
```

### 2.  Create A Virtual Environment


```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Download or Prepare Dataset

Use datasets like:

FaceForensics++

Deepfake Detection Challenge (DFDC)

Place real and fake videos into the data/ folder.

