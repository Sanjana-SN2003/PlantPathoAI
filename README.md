# PlantPathoAI - Plant Disease Detection Using Deep Learning 🌿

Problem Statement

Traditional methods for detecting plant diseases require manual inspection, which is time-consuming, inaccurate, and labor-intensive. Early detection of diseases is crucial for effective treatment and yield protection.
Overview 
PlantPathoAI is an AI-powered system that detects and classifies plant diseases using Deep Learning (DenseNet121). By analyzing leaf images,Video, it predicts diseases and provides causes & prevention measures to help farmers and researchers prevent crop loss.

Our Solution

We built an AI-powered Plant Disease Detection System using Convolutional Neural Networks (CNNs) with DenseNet121 to classify healthy and diseased plant leaves. The model also provides causes and preventive measures for identified diseases.

---

Key Features

✅ Automated Disease Detection – Upload a leaf image to detect plant diseases.
✅ Deep Learning Model (DenseNet121) – High accuracy classification of plant diseases.
✅ Cause & Prevention Analysis – Provides disease-related information.
✅ User-Friendly UI with Gradio – Easy-to-use web interface for predictions.
✅ Scalable & Real-Time – Can be deployed as a mobile/web application.

---

Dataset

Source: Kaggle (38 classes of plant leaves with different conditions)

Images: Preprocessed (resized to 256x256 pixels)

Classes: Bacteria, Fungi, Pest, Nematode, Virus, Phytophthora, and Healthy leaves

---

Model Architecture (DenseNet121)

Pretrained DenseNet121 model (trained on ImageNet) for feature extraction.
Fully connected layers for classification:
Flatten → Dense(512, ReLU) → Dropout
Dense(256, ReLU) → Dropout → Dense(7, Softmax)
Optimization: Adam Optimizer
Loss Function: SparseCategoricalCrossentropy
Training: Achieved ~90% accuracy

---

Image Preprocessing Steps

1️⃣ Upload an image
2️⃣ Resize to 256x256 pixels
3️⃣ Convert to NumPy array
4️⃣ Normalize pixel values (0-1)
5️⃣ Expand dimensions for model input

---

Tech Stack

Machine Learning

TensorFlow / Keras – Model training
CNN with DenseNet121 – Feature extraction
NumPy / OpenCV – Image processing

Frontend & Backend
Gradio – User-friendly web interface
Flask / FastAPI (Optional) – Backend for API deployment
Google Gemini API (Planned) – Future enhancements

---

Deployment & Scalability
Local Deployment: Run using Python & Gradio
Cloud Deployment: Can be hosted on AWS, Google Cloud, or Hugging Face Spaces
Mobile Integration: Future scope includes mobile app support

---

How to Use?

1. Install Dependencies
pip install tensorflow keras gradio numpy pandas matplotlib

2. Run the Model Locally
python app.py

3. Access Web UI
Open http://localhost:7860/ in your browser.

Upload a leaf image and get predictions.

---

Contributors

👩‍💻 Sanjana S N – Building Machine Learning model,UI
👨‍💻 Chandana S – Building Machine learning model,Framing Report
👩‍💻Bhumika A S-Web Ui& integrating ml model
👩‍💻 Archana A L – Building Ml Model

---

Future Enhancements

🚀 Google Gemini API Integration for more advanced insights.
📱 Mobile App Version for farmers & agricultural experts.
🔗 Blockchain Integration (Planned) for secure disease tracking.
---

References & Useful Links

📌 TensorFlow Docs – tensorflow.org
📌 Kaggle Dataset – Plant Disease Dataset
📌 GitHub Repository – [Your Repo Link Here]


---

License

This project is open-source under the MIT License.


