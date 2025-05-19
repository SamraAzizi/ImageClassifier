# 🖼️ AI Image Classifier

This is a simple web-based image classification app built with **Streamlit**, **TensorFlow (Keras)**, and **OpenCV**. It uses the pre-trained **MobileNetV2** model to identify the contents of uploaded images and returns the top 3 predictions.

---

## 🚀 Features

- Upload JPG or PNG images
- Classify images using the MobileNetV2 model trained on ImageNet
- Get top 3 predicted classes with confidence scores
- Simple and intuitive Streamlit UI

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install streamlit tensorflow opencv-python pillow numpy
```

## How To Run
1. save the scripts(e.g `main.py`)
2. Open your terminal and run:
```bash
streamlit run main.py
```

3. A browser window will open. Upload an image and click "Classify Image" to see predictions

## Model Details

- Model Used: `MobileNetV2