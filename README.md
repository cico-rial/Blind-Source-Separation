# 🎭 Blind Source Separation  

## 📌 About This Project  
This project tackles the **Blind Source Separation (BSS) problem**, where the goal is to **separate two superimposed images** - one from **MNIST** (digits) and the other from **Fashion-MNIST** (clothing items). We achieve this using a **U-Net architecture**, a powerful convolutional neural network designed for image-to-image tasks.  

## 🏆 Objective  
Given an input image that is a **sum of two different images**, the model learns to **decompose** it back into its original components:  
✅ **MNIST digit**  
✅ **Fashion-MNIST item**  

## 🛠 Methodology  
- 📌 **Dataset:** Overlapping images created by summing MNIST and Fashion-MNIST pairs.  
- 🏗 **Model Architecture:** U-Net, leveraging skip connections for precise reconstruction.  
- 🏋️ **Training Process:**  
  - Input: Superimposed images  
  - Output: Two separate grayscale images (one from each dataset)  
  - Loss function: **Mean Squared Error (MSE)** to minimize reconstruction error.  
- 📊 **Evaluation Metrics:** Mean Squared Error (MSE) and visual inspection of reconstruction quality.  

## 🔬 Results & Findings  
- The U-Net successfully learns to separate the two images, recovering both the **digit** and **fashion item** with minimal artifacts.  
- Performance improves with **careful hyperparameter tuning**.  

## 🚀 Getting Started  
### 📥 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
<!-- 
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

### 🏃 Running the Model  
To train the model, run:  
```bash
python train.py
```  
To test on new images, run:  
```bash
python predict.py --input_path your_image.png 
```  
-->

## ⚠️ Disclaimer  
This project is a **research-based experiment** in **image decomposition** using deep learning. It may not generalize well to other datasets without modifications.  

## 📬 Contact  
For any discussions or improvements, feel free to reach out!  
