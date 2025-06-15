# **Uncovering the Hidden Treasures of the Mushroom Kingdom: A Classification Analysis**

## 📌 **Project Summary**

This project explores the use of artificial intelligence to identify mushroom species from images. Using **transfer learning** with a pre-trained convolutional neural network, the system classifies mushrooms into three main categories — **Boletus**, **Lactarius**, and **Russula** — based on visual features like color, shape, and texture.

The objective is to build a lightweight, accurate, and scalable image classifier that can be useful in ecological research, food safety, and educational tools for nature lovers and students.

---

## 🖼️ **Preview Screenshots**

### 🌱 Home Interface

<p align="center">
 <img src="https://drive.google.com/uc?export=view&id=1yBSh7zuDdUp8OQcxDxwxwZCf2UYlkPQO" width="800">
</p>

### 🍁 Classification Output

<p align="center">
 <img src="https://drive.google.com/uc?export=view&id=1gQ9ZSEXVydIrZwm0XUdYouLbkYFCJnGp" width="800">
</p>

---

## ⚙️ **Setup Instructions**

### ✅ Using Conda (Preferred Method)

```bash
# Step 1: Create a dedicated environment
conda create -n mushroom_dl python=3.10

# Step 2: Activate the environment
conda activate mushroom_dl

# Step 3: Clone the repository
git clone https://github.com/YourUserName/your-repo.git
cd AI-Mushroom-Classification-Analysis-master

# Step 4: Install project dependencies
pip install -r requirements.txt
```

### 🔁 Using Python Virtual Environment

```bash
# Step 1: Create a venv
python -m venv venv_mushroom

# Step 2: Activate the environment
# Windows:
venv_mushroom\Scripts\activate
# Linux/macOS:
source venv_mushroom/bin/activate

# Step 3: Install all required packages
pip install -r requirements.txt
```

> ⚠️ **Note:** In some cases, you may need to manually install `Flask` and `TensorFlow` depending on your system environment.

---

## 🚀 **How to Launch the App**

```bash
cd Flask
python app.py
```

Once the server starts, visit your browser at:

👉 `http://localhost:5000`

---

##  **Directory Layout**

```
AI-Mushroom-Classification-Analysis-master/
├── Dataset/
│   ├── train/              # Training images
│   └── test/               # Test images
├── Flask/
│   ├── static/             # JavaScript and assets
│   ├── templates/          # HTML layout files
│   ├── uploads/            # Temporary user images
│   └── app.py              # Flask backend
├── IBM Files/              # Cloud deployment configs
├── Training files/         # Jupyter notebooks and scripts
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

##  **Model Design**

The image classifier is developed using **InceptionV3** through transfer learning. Fine-tuned layers were added to adapt the model for mushroom classification. The final model is saved as:

```
Mushroom Classification Model.h5
```

##  **Dataset Overview**

The dataset used for training and testing is organized into labeled folders:

* 📁 `Boletus`
* 📁 `Lactarius`
* 📁 `Russula`

Each image folder contains real-world photos to train the model to recognize mushrooms in natural environments.

---

## 🛠️ **Tech Stack**

* Python 3.10
* TensorFlow & Keras
* Flask (for web interface)
* OpenCV
* NumPy & Pandas
* HTML, CSS, JavaScript



## 🚧 **Planned Enhancements**

* Expand model to recognize more mushroom types
* Build a responsive mobile-friendly interface
* Add educational pop-ups with mushroom info
* Use GPS integration to enhance prediction based on region
* Improve dataset diversity for better real-world accuracy



## ✅ **Conclusion**

This AI-based mushroom classifier merges biology and deep learning into a practical tool for mushroom identification. By making mushroom recognition easier and faster, this project serves as a base for further research and smart applications in the field of botany, mycology, and conservation.
