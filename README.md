# 📷 Camera Classifier  

A Python-based **real-time image classifier** that uses a webcam to capture images, train an SVM model, and classify live video frames into two user-defined classes. Built with **Tkinter**, **OpenCV**, and **scikit-learn**, this project serves as an interactive tool to explore machine learning with real-time data.  

---

## ✨ Features  

- 🖼️ **Capture Images**: Take grayscale images for training the classifier.  
- 🤖 **Train SVM Model**: Train a Support Vector Machine (SVM) with your captured data.  
- 🔍 **Live Prediction**: Classify live webcam feed into one of two user-defined categories.  
- 🔄 **Reset**: Clear stored images and reset counters for fresh experiments.  

---

## 🗂️ File Descriptions  

### **`app.py`**  
This file provides the graphical user interface (GUI) for the application. It includes functionalities to:  
- Capture images for training.  
- Train the SVM model.  
- Predict live video frames.  

### **`camera.py`**  
Handles live video feed using OpenCV. Responsible for:  
- Grayscale conversion of video frames.  
- Capturing and saving images for training.  

### **`model.py`**  
Implements the Support Vector Machine (SVM) classifier with:  
- Methods for training the model using captured images.  
- Real-time prediction on video frames.  

### **`main.py`**  
The entry point of the program that initializes the GUI and integrates all components (`app.py`, `camera.py`, `model.py`).  

### **`__init__.py`**  
Marks the directory as a Python package, enabling modular imports.  

---

## 🚀 How to Run  

Follow these steps to set up and run the application:  

1. Clone this repository:  
   ```bash
   git clone https://github.com/AgambirSingh/Camera-Classifier.git  
   cd .Camera-Classifier  
   ```  

2. Install the library:  

   To run this project you need to import few libraries i guess you know how to do it

3. Run the application:  
   ```bash
   python main.py  
   ```  

4. Use the GUI to:  
   - Capture images for two classes.  
   - Train the SVM model.  
   - Classify live webcam feed into one of the two categories.  

---

## 🛠️ Possible Future Enhancements 

- 📊 **Extend to Multiple Classes**: Enable classification of more than two categories.  
- 🌐 **Web-Based Version**: Build a browser-compatible version of the application.  
- ⚙️ **Custom Models**: Add support for custom machine learning models (e.g., neural networks).  
- 📈 **Model Metrics**: Display accuracy and confusion matrix after training.  

## 🤝 Contributions  

Contributions are welcome! Please feel free to submit issues or pull requests to improve the application.  
