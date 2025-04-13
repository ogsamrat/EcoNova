# EcoNova 🌿🤖

**EcoNova** is a real-time, AI-powered biodiversity and threat monitoring system designed to detect wildlife, environmental hazards, and human threats using computer vision and machine learning. It integrates YOLOv8 for object detection and Linear Discriminant Analysis (LDA) for species classification, enhanced with Generative AI to produce natural language reports and predictive insights.

---

## 🚀 Features

- 🔍 Real-time object detection using **YOLOv8**
- 🧠 Species classification with **LDA + PCA**
- 🔥 Threat detection: fire, smoke, poaching & weapons
- 🌐 GPS-based location tagging for all events
- 📊 Dynamic dashboard
- 🧾 GenAI-generated reports and summaries
- ⚙️ Hardware-independent, modular, and scalable

---

## 🧰 Tech Stack

- **Python**  
- **YOLOv8** (`ultralytics`)  
- **OpenCV**, **NumPy**, **Matplotlib**  
- **scikit-learn** (LDA, PCA, DBSCAN)  
- **skimage** (GLCM Features)  
- **ThreadPoolExecutor** (for concurrent processing)  
- **Flask** (Dashboard)  
- **winsound**, **os**, **time** (for alerts & logging)  

---

## 🛠️ Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/ogsamrat/econova.git
   cd econova
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script  
   ```bash
   python main.py
   ```

---

## 🧪 How It Works

1. **Capture Data:** IoT-enabled cameras and sensors feed real-time data into the system.
2. **Preprocess Frames:** Frames are cleaned and optimized using OpenCV.
3. **Run Detection:** YOLOv8 detects objects and threats; LDA classifies animal species.
4. **Analyze Threats:** Rule-based logic and clustering evaluate risk levels.
5. **Generate Reports:** GenAI creates real-time summaries and insights.
6. **Trigger Alerts:** Audio/visual alerts and dashboard updates notify stakeholders instantly.

---

## 🌍 Use Cases

- Wildlife conservation and anti-poaching  
- Forest fire early-warning systems  
- Border surveillance and rural security  
- Disaster management and emergency response  
- Smart environmental monitoring

---

## 📁 Project Structure

```bash
econova/
├── data/                   # Sample datasets
├── models/                 # Trained model files
├── utils/                  # Helper functions
├── dashboard/              # Flask UI
├── main.py                 # Main execution script
├── report_generator.py     # GenAI module
├── requirements.txt
└── LICENSE
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues, suggest enhancements, or submit pull requests. However, please note that this project is **not open-source**, and contributions must comply with the licensing terms.

---

## 📜 License

This project is licensed under a **Proprietary License**. While the code is **publicly visible**, it is **not open source**. Redistribution, modification, or commercial use of the code is prohibited without **explicit written permission** from the author.  
See the [LICENSE](LICENSE) file for full details.

---

## 💬 Acknowledgements

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)  
- [scikit-learn](https://scikit-learn.org/)  
- [OpenCV](https://opencv.org/)  

---

## 🌟 Star the repo if you find it helpful!
