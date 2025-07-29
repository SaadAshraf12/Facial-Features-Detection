
### **Facial Features Detection System**

This project focuses on detecting key facial features from images using deep learning and computer vision techniques. The system performs three main tasks:

1. **Gender Classification**
2. **Glasses Detection**
3. **Shirt Color Recognition**

---

### **🧠 Models & Tools Used**

* **EfficientNetB0** (for Gender & Glasses Detection)
* **MediaPipe** (for Face & Torso Detection)
* **K-Means Clustering** (for Shirt Color Extraction)

---

### **📊 Dataset Summary**

* **Gender Dataset**: 1530 images (765 male / 765 female)
* **Glasses Dataset**: 2000 images (1000 with glasses / 1000 without glasses)
* **Collection Method**:

  * Scraped online image links using Python
  * Cropped faces using MediaPipe
  * Manually filtered for quality

---

### **⚙️ Why EfficientNetB0?**

* Lightweight, fast, and accurate
* Pretrained on ImageNet
* Performs well on small and diverse datasets
* Scalable architecture ideal for transfer learning

---

### **⏱ Inference Time**

* **Gender Prediction**: \~0.09–0.12 sec
* **Glasses Prediction**: \~0.09–0.12 sec
* **Shirt Color Detection**: \~0.09–0.4 sec

---

### **⚠️ Limitations**

* Glasses detection may fail with side poses
* Shirt color may be inaccurate due to lighting/shadows
* Torso detection can fail if the person is not upright or partially visible

---

### 📁 **Folder Includes**

* Notebooks
* Trained Weights
* Instructions to run (`README.md`)

> Upload or capture a face image → Get gender, glasses status, and shirt color as output.

