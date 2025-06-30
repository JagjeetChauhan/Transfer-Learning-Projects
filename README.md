# 🔁 Transfer Learning Projects

This repository showcases deep learning projects built using **transfer learning** techniques with PyTorch. Transfer learning allows leveraging powerful pretrained models on large datasets and fine-tuning them for specific tasks, saving time and improving performance.

---

## 📁 Projects

### 1. 🍕 Food Classifier

**Description:**  
A food image classifier that identifies food items from three categories: **Pizza**, **Steak**, and **Sushi**. It demonstrates how transfer learning can be used for multi-class classification with a relatively small, custom dataset.

**Highlights:**
- Uses `efficientnet_b0` pretrained on ImageNet
- Custom dataset with three food categories
- Data augmentation and preprocessing
- Fine-tuning and training
- Achieves high accuracy with few samples

---

### 2. 🌸 Flower Classifier

**Description:**  
This project classifies images from the **Oxford 102 Flower** dataset, which contains 8,000+ images spanning 102 flower categories with high intra-class variation.

**Highlights:**
- Uses `efficientnet_b0` for feature extraction and fine-tuning
- Data augmentation to handle class imbalance
- Evaluation with metrics like accuracy and loss
- Transfer learning approach significantly boosts performance

---

## 🔧 Technologies Used

- Python 3
- PyTorch
- Torchvision
- EfficientNet B0 (pretrained on ImageNet)
- Matplotlib (for visualizations)
