
---

# 🌿 Plant AI Engine – Smart Plant Disease Detection & Support Hub

**Plant AI Engine** is a smart, web-powered platform that brings the power of AI to plant health. Designed with simplicity and utility in mind, it allows users to **diagnose plant leaf diseases** by simply uploading or capturing an image. Beyond detection, the platform also offers **custom treatment tips**, **fertilizer suggestions**, and a **borrowing system for essential gardening items**.

Whether you’re a home gardener or an agriculture enthusiast, Plant AI Engine is your intelligent assistant for healthy plants.

---

## 🔍 Core Capabilities

* 📷 **Detect diseases** from plant leaf images (upload or use rear camera)
* 🧠 **AI-driven prediction** with a trained machine learning model
* 💊 **Get insights** on disease management and treatment
* 🌱 **Access suggestions** on fertilizers and care routines
* 🧺 **Borrow tools & supplements** directly from the platform
* 📱 **Fully responsive** design for mobile and desktop browsers

---
---

## 📸 Application Screenshots

Here are some previews of the Plant AI Engine interface in action:

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/Chatur07/Plant-AI-Engine/blob/main/demo_images/ss1.png" width="600" alt="Homepage Screenshot"/>
    </td>
    <td align="center">
      <img src="https://github.com/Chatur07/Plant-AI-Engine/blob/main/demo_images/ss2.png" width="600" alt="Login Page Screenshot"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/Chatur07/Plant-AI-Engine/blob/main/demo_images/ss3.png" width="600" alt="Disease Detection Screenshot"/>
    </td>
    <td align="center">
      <img src="https://github.com/Chatur07/Plant-AI-Engine/blob/main/demo_images/ss4.png" width="600" alt="Borrow Essentials Screenshot"/>
    </td>
  </tr>
</table>


---


## ⚙️ Tools & Technologies

**Backend:**

* `Python`, `Flask` – powering the logic and ML integration

**Frontend:**

* `HTML`, `CSS`, `JavaScript` – interactive and adaptive UI

**Machine Learning:**

* Trained model using `scikit-learn` or `TensorFlow` *(depending on model used)*

**Supporting Libraries:**

* `Pillow` – preprocesses images
* `Pandas` – fetches disease-related data
* `Flask` – builds the server & routes

---

## 🗂️ Project Directory Overview

```
Plant-AI-Engine/
│
├── static/            # Static files (stylesheets, JS)
├── templates/         # Jinja2 HTML templates
├── model/             # ML model files
├── uploads/           # Images uploaded by users
├── app.py             # Main application script
├── requirements.txt   # Python dependencies
└── README.md          # This file
```

---

## 🚀 Quickstart Guide

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/Plant-AI-Engine.git
cd Plant-AI-Engine
```

### Step 2: Setup Virtual Environment

**Windows:**

```bash
python -m venv env
env\Scripts\activate
```

**macOS/Linux:**

```bash
python3 -m venv env
source env/bin/activate
```

### Step 3: Add Required Libraries

Create a file named `requirements.txt` with:

```
Flask
pandas
Pillow
scikit-learn
```

> 🧠 *Include any additional packages your project uses.*

Then install:

```bash
pip install -r requirements.txt
```

### Step 4: Add the ML Model

Place your pre-trained model (`plant_disease_model_1.pt`) in the root directory or the `model/` folder.
Download here [https://drive.google.com/file/d/1VowRxSkoRXXkOD07uBc-8uPY6sWvWiHY/view?usp=sharing]

### Step 5: Start the Server

```bash
python app.py
```

Visit in your browser:
🌐 [http://127.0.0.1:5000]

---

## 🖼️ What You’ll See

* **Homepage** – Clean UI with options to detect disease or borrow tools
* **Login System** – Simple user login (optional for borrowing)
* **AI Detection Page** – Upload or capture leaf images, get instant results
* **Essentials Page** – Request fertilizers, tools, and supplements
* **Contact Page** – Leave feedback or queries

---

## ✅ Completed Features Summary

* Frontend UI: Designed using Bootstrap + custom CSS
* Rear camera access integrated via JS (mobile-friendly)
* Image preprocessing with Pillow
* ML classification using pre-trained model
* CSV-based recommendation system via Pandas
* Borrowing request functionality for tools and care items

---

## 📄 License

Distributed under the [MIT License](LICENSE).
Feel free to fork, use, and improve!

---


