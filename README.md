# 🧠 Deep Learning Image Classification Suite

A comprehensive Image Classification repository implementing multiple state-of-the-art Convolutional Neural Network architectures with full training, evaluation, transfer learning and deployment pipeline.

This project demonstrates practical understanding of Computer Vision model development from research architectures to real-world applications.

---

## 🚀 Project Highlights

* Multiple CNN Architectures implemented from scratch
* Transfer Learning using pretrained weights
* Modular training pipeline
* Data preprocessing & augmentation
* Model evaluation & visualization
* Deployment ready structure

---

## 🏗️ Architectures Implemented

* AlexNet
* VGG16 / VGG19
* ResNet18 / ResNet50
* EfficientNet

Each architecture includes:

* Custom implementation
* Pretrained version
* Fine-tuning support

---


## ⚙️ Installation

```bash
git clone https://github.com/yourusername/image-classification-suite.git

cd image-classification-suite

pip install -r requirements.txt
```

---

## ▶️ Training Models

Train different architectures using:

```bash
python train.py --model resnet50 --epochs 25
```

Supported models:

* alexnet
* vgg16
* resnet18
* resnet50
* efficientnet

---

## 🔥 Transfer Learning

The repository supports transfer learning to:

* reduce training time
* improve accuracy
* adapt to small datasets

Example:

```python
model.fc = nn.Linear(model.fc.in_features, num_classes)
```

---

## 📊 Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📈 Visualization

* Training vs Validation curves
* Grad-CAM attention maps
* Prediction visualization

---
---

## 🧩 Future Enhancements

* Model Quantization
* ONNX Export
* Distributed Training
* Hyperparameter tuning automation

---

## 🤝 Contributing

Feel free to fork and improve the project.

---

## ⭐ Star the repo if you find it useful!
