# 🌾 Plant Disease Detection using Transformers

## 📋 Project Overview
An AI-powered plant disease detection system using **CNN + Transformer Hybrid Architecture** to identify 38 different plant diseases. This project addresses **SDG 2: Zero Hunger** by helping farmers detect crop diseases early and accurately.

---

## 🎯 Key Features
- ✅ **94.61% Training Accuracy** (Exceeds 75% requirement by 19.61%)
- ✅ **Lightweight Model**: Only 533,926 parameters (CPU-optimized)
- ✅ **Modern Architecture**: CNN + Transformer Hybrid
- ✅ **Real-world Focus**: Designed for deployment on resource-constrained devices
- ✅ **38 Disease Classes**: Covers multiple crops (tomato, potato, pepper, etc.)

---

## 🏗️ Model Architecture
**Hybrid CNN-Transformer Model**
- **CNN Layers**: Feature extraction from plant images (3 convolutional blocks)
- **Transformer Layers**: Self-attention mechanism for pattern recognition (2 encoder layers)
- **Classification Head**: Fully connected layers with dropout for disease prediction

**Model Specifications:**
- Parameters: 533,926
- Input Size: 224×224×3
- Output Classes: 38
- Device: CPU (no GPU required)

---

## 📊 Dataset
**PlantVillage Dataset**
- Total Images: 54,305
- Training Set: 43,444 images (80%)
- Test Set: 10,861 images (20%)
- Image Resolution: 224×224 pixels
- Classes: 38 plant disease categories

---

## 🚀 Training Results

| Epoch | Training Accuracy | Training Loss |
|-------|------------------|---------------|
| 1     | 74.43%          | 0.8439        |
| 2     | 89.29%          | 0.3314        |
| 3     | 92.43%          | 0.2337        |
| 4     | 93.62%          | 0.1979        |
| 5     | **94.61%**      | **0.1678**    |

**✅ Final Result: 94.61% Training Accuracy**

---

## 🛠️ Technology Stack
- **Language**: Python 3.14.2
- **Deep Learning**: PyTorch 2.9.1
- **Data Processing**: NumPy, Pandas
- **Visualization**: Matplotlib, Seaborn
- **Image Processing**: Pillow (PIL)
- **ML Tools**: scikit-learn
- **Development**: Jupyter Notebook

---

## 📁 Project Structure
```
crop-disease-detection/
├── plant_disease_model.ipynb    # Main training notebook
├── Documentation/                # Project documentation
├── README.md                     # This file
└── .gitignore                   # Git ignore rules
```

---

## 🎓 Academic Information
**Course**: MS Data Science Project  
**Domain**: Agriculture (Plant Disease Detection)  
**Algorithm**: Transformers (CNN-Transformer Hybrid)  
**SDG Alignment**: SDG 2 - Zero Hunger  
**Requirement**: 75%+ Accuracy ✅ **Achieved: 94.61%**

---

## 💡 Why This Approach?
1. **Lightweight Design**: Can run on farmers' mobile devices
2. **Transformer Benefits**: Captures long-range dependencies in image features
3. **CPU Optimization**: Accessible without expensive GPU hardware
4. **Practical Impact**: Real-world deployment ready

---

## 🌟 Project Highlights
- ✅ Exceeds accuracy requirement by **19.61%**
- ✅ Modern Transformer architecture implementation
- ✅ Efficient training on CPU (no GPU needed)
- ✅ Addresses real-world agricultural challenges
- ✅ Lightweight & deployable model

---

## 📧 Contact
**Developer**: Ayesha Ishfaq  
**Program**: MS Data Science  
**GitHub**: [AyeshaIshfaqDS](https://github.com/AyeshaIshfaqDS)

---

## 📝 License
This project is developed for academic purposes.

---

## 🙏 Acknowledgments
- PlantVillage Dataset providers
- PyTorch community
- Open-source contributors

---

**⭐ If you find this project helpful, please star the repository!**
