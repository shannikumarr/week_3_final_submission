# ♻️ Waste Material Image Classifier

This project is an image classification app that uses a trained deep learning model to identify types of waste — including cardboard, glass, metal, paper, plastic, and trash. It uses a **TensorFlow model** with **Gradio UI** for easy interaction and deployment.

## 🔍 Demo
Try it live: [Hugging Face Space](https://huggingface.co/spaces/k087/garbage_classification)

---

## 🧠 Model Info

- Model architecture: `MobileNetV2`
- Input size: `224x224x3`
- Preprocessing: Raw images (0–255 float values)
- Trained on: Custom waste classification dataset
- Classes:
  - `cardboard`
  - `glass`
  - `metal`
  - `paper`
  - `plastic`
  - `trash`

---

## 🚀 How to Use

1. Upload or drag an image of trash.
2. The model will classify it into one of 6 waste categories.
3. View the predicted class and confidence score instantly.

---

## 📁 Files in This Repo

| File               | Description                                  |
|--------------------|----------------------------------------------|
| `app.py`           | Main Gradio interface and prediction script  |
| `best_mobilenetv2.keras` | Trained Keras model                        |
| `requirements.txt` | Python dependencies for Hugging Face         |
| `README.md`        | You're reading it!                           |

---

## 🛠 Requirements

Make sure these packages are available (automatically installed on Hugging Face Spaces):

```txt
tensorflow
gradio
numpy
Pillow
