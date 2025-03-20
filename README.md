🌿 Leaf Disease Detection App


The Leaf Disease Detection App is a machine learning-based application designed to help farmers, gardeners, and agricultural professionals identify plant diseases from leaf images. The app uses a deep learning model to classify diseases and provides detailed information about the disease, its severity, causes, and prevention methods. It also supports real-time camera capture and video stream analysis.

Features
Disease Classification: Detects and classifies diseases in plant leaves into seven categories:
Bacteria
Fungi
Healthy
Nematode
Pest
Phytopthora
Virus

Real-Time Camera Support: Capture images using your device's camera for instant disease detection.
Video Stream Analysis: Analyze video streams (e.g., from drones) for disease detection.
Text-to-Speech: Provides audio feedback for disease diagnosis and prevention tips.
User-Friendly Interface: Built with Gradio, the app is easy to use and accessible to non-technical users.

Technologies Used
Deep Learning:
Model: DenseNet121 with custom layers (Batch Normalization, Dropout, Dense layers).
Framework: TensorFlow and Keras.
Computer Vision: OpenCV for real-time camera and video stream processing.
Text-to-Speech: gTTS (Google Text-to-Speech) for audio feedback.
User Interface: Gradio for building the web-based interface.
Data Management: Pandas for handling disease information stored in a CSV file.

Usage
Upload Image:
Go to the Upload Image tab.
Upload a leaf image and click Submit.
The app will display the disease name, severity, cause, and prevention tips.
![Image](https://github.com/user-attachments/assets/bce19b59-1b3b-44b2-85e4-e5a5a67b19db)
Real-Time Camera:
Go to the Real-Time Camera tab.
Click Capture Image to take a photo using your device's camera.
The app will analyze the image and provide results.
![Image](https://github.com/user-attachments/assets/a3b7e143-6803-43c9-813d-fbac1b911d73)
Video Stream Analysis:
Go to the Video Stream Analysis tab.
Upload a video file or provide a stream URL.
Click Analyze Video to process the video and detect diseases.

Chatbot:
Go to the Chatbot tab.
Ask questions about plant diseases (e.g., "What causes fungal infections?").
The chatbot will provide detailed responses with audio feedback.

Dataset
The model was trained on a dataset containing 3,076 images of plant leaves, categorized into seven classes:
Bacteria
Fungi
Healthy
Nematode
Pest
Phytopthora
Virus

Dataset_link=https://www.kaggle.com/datasets/nirmalsankalana/potato-leaf-disease-dataset

Model Performance
Test Accuracy: 95.17%
Loss: 0.1659

Future Improvements
Support for more plant species and diseases.
Integration with mobile apps for on-the-go disease detection.
Enhanced video stream analysis for large-scale agricultural monitoring.
Multi-language support for text-to-speech feedback.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes.
Submit a pull request.

Acknowledgments
TensorFlow and Keras for providing the deep learning framework.
Gradio for the user-friendly interface.
OpenCV for real-time image and video processing.
gTTS for text-to-speech functionality.
![Image](https://github.com/user-attachments/assets/6bb1028c-2b80-44de-8e62-0c7e67c800e1)
