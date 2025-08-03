# 🧠 CV_SelfDriving_Cars

Final project for the **IBM AI Engineering Professional Certificate** (Coursera).  
This project demonstrates how computer vision and deep learning techniques can be applied to simulate key tasks in a self-driving car pipeline, including lane detection, object recognition, and behavioral cloning.

---

## 🚗 Project Overview

This project applies computer vision and deep learning techniques to develop essential components of a self-driving car system. The goal is to showcase model development and training for perception tasks, using real-world datasets and Python-based tools.

**Key Components:**
- Lane detection using OpenCV and image processing
- Object detection using pre-trained models (e.g., YOLO, SSD)
- End-to-end behavioral cloning using Convolutional Neural Networks (CNNs)

---

## 🧰 Tools & Technologies

- Python 3.x
- OpenCV
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Jupyter Notebooks
- Pre-trained models (YOLO, MobileNet, etc.)

---

## 📁 Repository Structure

CV_SelfDriving_Cars/
├── data/ # (optional) Sample datasets (not pushed to GitHub)
├── notebooks/ # Jupyter notebooks for EDA, training, evaluation
│ ├── lane_detection.ipynb
│ ├── object_detection.ipynb
│ └── behavioral_cloning.ipynb
├── src/ # Modular Python scripts
│ ├── data/ # Data loaders and transformers
│ ├── models/ # Model definitions and training scripts
│ └── utils/ # Helper functions
├── reports/ # Results, plots, and summary
├── requirements.txt # Python dependencies
├── environment.yml # (optional) Conda environment file
├── README.md # Project overview (this file)
└── LICENSE # Open source license (MIT)

yaml
Copy
Edit

---

## 📊 Results Summary

| Task                | Technique            | Accuracy / Output |
|---------------------|----------------------|-------------------|
| Lane Detection      | OpenCV + Canny       | Real-time overlay |
| Object Detection    | YOLOv3 (pre-trained) | Detected cars, signs |
| Behavioral Cloning  | CNN (Keras)          | 0.02 MSE (simulated) |

---

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/yourusername/CV_SelfDriving_Cars.git
cd CV_SelfDriving_Cars
Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Run Jupyter Notebooks
bash
Copy
Edit
jupyter notebook
📚 Course Information
This project was developed as the final capstone for the
🎓 IBM AI Engineering Professional Certificate on Coursera.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙋‍♂️ Acknowledgments
IBM & Coursera for the curriculum

Udacity Self-Driving Car dataset (optional)

YOLO authors for pre-trained weights
