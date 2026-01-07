🚢 Naval Ship Detection and Classification using YOLOv8

An AI-based Naval Ship Detection and Classification System built using YOLOv8 and Deep Learning, designed to automatically detect and classify different classes of naval vessels from maritime imagery.
The system is optimized for real-time inference, high accuracy, and scalable deployment.

📌 Project Overview

Naval surveillance is a critical task for maritime security and defense systems. Manual monitoring is inefficient and error-prone, especially under varying weather and sea conditions.

This project leverages YOLOv8 for real-time object detection and integrates federated learning concepts to enable collaborative model training without centralized data sharing.

🎯 Objectives

Detect naval ships from satellite / aerial / maritime images

Classify ships into multiple naval categories

Achieve real-time detection performance

Enable scalable and privacy-aware training using federated learning

Provide a simple web-based interface for testing and visualization

🧠 Key Features

⚡ YOLOv8-based object detection

🚢 Multi-class naval ship classification

🔐 Federated learning-based training workflow

🌐 Web interface for inference

📦 Pre-trained models managed using Git LFS

🖼️ Image upload and result visualization

🏗️ System Architecture
User Image Upload
        ↓
Image Preprocessing
        ↓
YOLOv8 Model Inference
        ↓
Ship Detection & Classification
        ↓
Result Visualization (Bounding Boxes + Labels)

📂 Project Structure
Naval_Ship_Major_Project_Final/
│
├── app.py                  # Main application entry point
├── chatbot.py              # AI chatbot / assistant logic
├── config.py               # Configuration settings
├── requirements.txt        # Python dependencies
├── test_azure.py           # Azure/OpenAI testing script
│
├── model/                  # YOLOv8 trained models (Git LFS)
│   ├── best.pt
│   ├── last.pt
│   ├── yolov8n.pt
│   └── federated_yolov8_naval.pt
│
├── static/
│   ├── style.css
│   └── results.jpg
│
├── templates/
│   └── index.html
│
├── uploads/
│   ├── input.jpg
│   └── output.jpg
│
├── .gitignore
├── .gitattributes          # Git LFS configuration
└── README.md

🧪 Model Details

Model Architecture: YOLOv8 (Ultralytics)

Detection Type: Object Detection + Classification

Training Approach:

Centralized YOLO training

Federated learning simulation across multiple clients

Model Format: .pt (PyTorch)

Model Storage: Git LFS (Large File Storage)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/PatelNandini30/Naval-Ship-Detection.git
cd Naval-Ship-Detection

2️⃣ Create Virtual Environment
python -m venv venv


Activate:

Windows

venv\Scripts\activate


Linux / macOS

source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

▶️ Run the Application
python app.py


Then open your browser and visit:

http://localhost:5000


Upload an image to perform naval ship detection.

📊 Results

Accurate detection of naval vessels

Clear bounding boxes and class labels

Robust performance under diverse conditions

Efficient inference suitable for real-time systems

🔐 Git LFS Note

This project uses Git Large File Storage (LFS) to manage trained model files (.pt).

If cloning for development:

git lfs install
git lfs pull

🚀 Future Enhancements

Real-time video stream detection

Integration with satellite data pipelines

Advanced federated learning using Flower (FLWR)

Model explainability and confidence scoring

Deployment on cloud platforms (Azure / AWS)

🎓 Academic Relevance

Domain: Artificial Intelligence / Computer Vision

Use Case: Defense & Maritime Surveillance

Tech Stack: YOLOv8, PyTorch, Flask, Federated Learning

Project Type: Major Project / Capstone

👩‍💻 Author

Nandini Patel
Department of Computer Engineering
Major Project – Naval Ship Detection & Classification

📜 License

This project is licensed under the MIT License.
