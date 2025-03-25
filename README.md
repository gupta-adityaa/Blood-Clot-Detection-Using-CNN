# **Blood Clot Detection using Deep Learning**

## **Overview**
This project implements **deep learning techniques** to automatically detect **blood clots** in medical images. Using **EfficientNet B1** and **ResNet50**, we achieve **high accuracy (above 99%)**, making the system a powerful tool for early diagnosis of thrombotic diseases.

## **Key Features**
- ✅ **Deep Learning Models**: EfficientNet B1 & ResNet50
- ✅ **High Accuracy**: 99.60% (EfficientNet B1), 99.51% (ResNet50)
- ✅ **Medical Image Analysis**: Classifies blood clot images with precision
- ✅ **Dataset**: 19,998 images (collected from Kaggle)
- ✅ **Performance Metrics**: Accuracy, Precision, Recall, Sensitivity, and Specificity
- ✅ **Hyperparameter Tuning**: Optimized for best performance
- ✅ **Data Augmentation**: Improves model generalization

## **Dataset**
The dataset consists of:
- 📌 **Positive (Clot images)**: 9,999 images
- 📌 **Negative (No clot images)**: 9,999 images
- 📌 **Metadata File**: Contains labels for classification

## **Model Architectures**
- **EfficientNet B1**: Optimized for depth, width, and resolution scaling.
- **ResNet50**: Uses deep residual connections to prevent vanishing gradient problems.

## **Implementation Details**
- **Programming Language**: Python (TensorFlow, Keras)
- **Hardware Setup**:
  - **GPU**: NVIDIA RTX 3050 (4GB VRAM)
  - **CPU**: Intel i5 11th Gen
  - **RAM**: 8GB
  - **OS**: Ubuntu 22.04 LTS

## **Results**
| Model       | Accuracy | Precision | Recall | Sensitivity | Specificity |
|------------|----------|-----------|--------|-------------|-------------|
| EfficientNet B1 | 99.60% | 99.48% | 99.73% | 99.73% | 99.48% |
| ResNet50        | 99.51% | 99.67% | 99.34% | 99.34% | 99.67% |

## **Installation & Usage**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/gupta-adityaa/BloodClotDetection.git
cd BloodClotDetection
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

## **Future Scope**
- 🚀 **Integrate real-time image processing**
- 🚀 **Expand dataset for better generalization**
- 🚀 **Deploy as a web-based diagnostic tool**
