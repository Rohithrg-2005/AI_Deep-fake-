# 🧠 Deepfake Detection with Security Layer

## 📌 Overview

This project implements a simple deepfake detection system that classifies images as **Real** or **Fake**.
If an image is detected as **Real**, additional security mechanisms are applied to protect the content.

---

## 🎯 Features

* ✅ Detects whether an image is **Real or Fake**
* 🔐 Adds **Watermark** to real images
* 🔑 Generates **SHA-256 Hash** for integrity
* 📦 Simulates **Blockchain Storage**
* ⚡ Simple and fast implementation

---

## 🧩 Project Workflow

```
Input Image
     ↓
Deepfake Detection (Real / Fake)
     ↓
If Real → Watermark + Hash + Blockchain
If Fake → Display Fake
```

---

## 📂 Dataset Structure

```
dataset/
   ├── real/
   │     ├── real_00001.jpg
   │     ├── ...
   ├── fake/
         ├── fake_00001.jpg
         ├── ...
```

* `real/` → Original images
* `fake/` → Deepfake images

---

## ⚙️ Installation

```bash
pip install numpy opencv-python
```

---

## ▶️ How to Run

```python
predict_image("dataset/real/real_00001.jpg")
```

---

## 🧠 How It Works

* The system analyzes the image
* Classifies it as **Real** or **Fake**
* If Real:

  * Adds watermark
  * Generates hash
  * Stores record in blockchain (simulated)

---

## 🧪 Example Output

```
Real Image ✅
Hash: d6708228d3b1c199...
Stored in Blockchain
```

or

```
Fake Image ❌
```

---

## 🎓 Conclusion

This project demonstrates a basic pipeline for:

* Deepfake detection
* Content authentication and security

---

## 📌 Future Improvements

* Use advanced CNN models for better accuracy
* Add real blockchain integration
* Extend to video deepfake detection

---

## 👨‍💻 Author

* Rohith Guda
* Yatharth thiwari
* Rishi varma
