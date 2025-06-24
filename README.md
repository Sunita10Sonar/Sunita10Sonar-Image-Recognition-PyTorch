# 🐶 Image Recognition using Pre-trained CNN Models with PyTorch

This project demonstrates how to perform **image classification using pre-trained deep learning models** (such as **AlexNet** and **ResNet101**) from the `torchvision.models` library. The project uses **PyTorch** and **Google Colab** for a seamless deep learning workflow.

---

## 🔍 Overview

We classify input images (like `dog.png`) using pretrained models without training from scratch. The models predict image labels using features learned from ImageNet.

---

## 🧠 Key Concepts

- **Preprocessing** with `torchvision.transforms` to match ImageNet requirements
- Use of **pretrained CNNs** (`AlexNet`, `ResNet101`)
- Image loading and inference using `PIL`, `PyTorch`, and `Colab`
- Predicting and visualizing model output labels

---

## 🔧 Technologies & Tools

- Python
- PyTorch
- Torchvision
- PIL
- Google Colab
- CNN Architectures: AlexNet, ResNet101

---

## 💡 Workflow

1. Load pretrained models (`AlexNet`, `ResNet101`)
2. Preprocess the input image
3. Pass the image tensor through the model
4. Use softmax to interpret model output
5. Map predicted index to class label using ImageNet labels

---

## 📈 Sample Output

Example:
> Input Image: 🐶 `dog.png`  
> Predicted Class: `"Golden Retriever"`
> Accuracy: '**96%**'
---


