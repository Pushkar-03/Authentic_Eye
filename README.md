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


🧠 Model Training
To train the model from scratch:

```bash
python train_model.py
```
You can configure parameters like:
1) Epochs
2) Batch size
3) Learning rate

Model architecture (ResNet)

🌐 Run the Flask Web App
To launch the web interface:

```bash
python app.py
```
Then open "http://127.0.0.1:5000" in your browser and upload a video to test deepfake detection.

📊 Sample Output
Real-time prediction (Real / Fake)

Confidence scores

Visual feedback of detected faces

📌 Future Improvements
🎙️ Audio deepfake detection integration

🧠 Lightweight models for mobile deployment

📈 Real-time video stream analysis

🛡️ Integration with cybersecurity alert systems

🧾 License
This project is licensed under the MIT License. Feel free to use and modify it for educational or research purposes.

🤝 Contributing
Contributions are welcome! Open an issue or pull request to suggest improvements, add models, or enhance the UI.

📬 Contact
For collaborations or inquiries:
📧 [phbstudy@gmail.com]
🔗 LinkedIn: www.linkedin.com/in/pushkar-bihani  (Pushkar Bihani)

---

## Let me know if you want this tailored for Hugging Face Spaces, Docker deployment, or want to include pretrained model links.

