# 🌼 Pollen Classification Web Application

This project is a Flask-based web application for classifying pollen grain images using a trained Convolutional Neural Network (CNN). It includes image preprocessing, model training, and a web interface for prediction, team info, and contact.

---

## 🚀 Features

* 🌸 Deep learning model to classify pollen grains
* 🖼 Upload images and get predictions instantly
* 🎨 Modern UI with pages: Home, About, Prediction, Our Team, Contact
* 📈 Visualization of training metrics
* 🧠 Model trained using TensorFlow and Keras

---

## 🛠 Technologies Used

* Python 3.11+
* Flask 3.x
* TensorFlow 2.x
* Keras
* OpenCV
* Scikit-learn
* NumPy, Pandas, Matplotlib
* HTML5, CSS3 (Glassmorphism UI)
* Jupyter Notebook (for model development)

---

## 📂 Project Structure

```
├── app.py                    # Flask backend application
├── pollen_classification.ipynb  # Model training and evaluation notebook
├── pollen_model.keras        # Trained CNN model
├── labelencoder.pkl          # Saved label encoder
├── requirements.txt          # Dependencies list
├── templates/                # HTML templates (Jinja2)
│   ├── index.html
│   ├── about.html
│   ├── prediction.html
│   ├── team.html
│   └── contact.html
├── static/                   # Static assets (CSS, images)
│   ├── style.css             # Global stylesheet
│   └── images/               # Logo and team/profile images
├── uploads/                  # Uploaded images for prediction (temporary)
└── LICENSE                   # MIT License for the project
```

---

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/pollen-classification-app.git
cd pollen-classification-app
```

2. **Create a virtual environment (recommended):**

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the App

```bash
python app.py
```

Then open your browser and go to:
📍 `http://127.0.0.1:5000/`

---

## 🧪 Model Training

If you want to retrain the model or modify it:

* Open `pollen_classification.ipynb` in Jupyter Notebook.
* Make sure `pollen_dataset/images/`, `bboxes.csv`, and `class_map.csv` are properly placed.
* Execute all cells to preprocess data, train the CNN, and export:

  * `pollen_model.keras`
  * `labelencoder.pkl`

---

## 📸 Prediction Demo

* Navigate to the **Prediction** page in the app.
* Upload a cropped pollen grain image.
* The model will return the predicted class with high accuracy.

---

## 👥 Team

Meet our amazing contributors on the **Our Team** page!

---

## 📬 Contact

Feel free to reach out via the **Contact** page with suggestions, feedback, or collaboration ideas!
