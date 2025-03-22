# 🧠 Deep Learning Model Training & Visualization  

## 🚀 Project Overview  
This project implements and visualizes multiple deep learning models using **TensorFlow/Keras**. It includes:  
✔️ Data preprocessing & exploration  
✔️ Building & training different models (Basic NN, CNN, ViT, and a combined CNN+ViT model)  
✔️ Saving models & visualizing architectures  
✔️ Evaluating and summarizing model performance  

---

## 🛠 Dependencies  
Ensure you have the following Python libraries installed before running the notebook:  
```bash
pip install tensorflow matplotlib seaborn numpy pandas pydot graphviz
```

---

## 💟 How to Run  
1️⃣ Open the Jupyter Notebook (`Sessional.ipynb`) in **Jupyter Lab or Colab**.  
2️⃣ Run each cell sequentially to train and evaluate the models.  
3️⃣ Model architecture plots will be **saved and displayed**.  
4️⃣ Final trained models are **saved in `.h5` format** for further use.  

---

## 📊 Model Performance Summary  
The table below summarizes the accuracy of each model:  

| 🏆 Model        | 🎯 Accuracy |
|---------------|------------|
| 🧬 Basic NN   | **87.67%** |
| 🖼️ CNN        | **92.88%** |
| 🌀 ViT        | **85.39%** |
| 🔗 CNN+ViT   | **94.3%** |

_(These values are placeholders; update them after training your models.)_  

---

## 🔍 Data Preprocessing  
✔️ Checked for **missing values**  
✔️ Normalized **pixel values to [0,1]**  
✔️ **One-hot encoded** the labels  
✔️ Explored **data distribution**  

---

## 🏢 Model Architectures  

### 🧬 1. Basic Neural Network (NN)  
- A simple **fully connected feedforward network**  
- Uses **dense layers** with ReLU activation  
- Suitable for **basic classification tasks**  
- Architecture is saved as `basic_model_architecture.png`  

### 🖼️ 2. Convolutional Neural Network (CNN)  
- Extracts **spatial features** from images  
- Uses **Conv2D, MaxPooling, Flatten, and Dense layers**  
- Architecture is saved as `cnn_model_architecture.png`  

### 🌀 3. Vision Transformer (ViT)  
- Uses **self-attention mechanism** for feature extraction  
- Processes images as **patch embeddings**  
- Powerful for **complex pattern recognition**  
- Architecture is saved as `vit_model_architecture.png`  

### 🔗 4. Combined CNN + ViT  
- **Hybrid model combining CNN feature extraction with ViT attention**  
- Achieves **higher accuracy** than individual models  
- Architecture is saved as `combined_model_architecture.png`  

---

## 📉 Future Improvements  
🚀 Hyperparameter tuning for **better accuracy**  
📈 Experimenting with **larger datasets**  
🔍 Trying advanced models like **ResNet, EfficientNet**  

---

## 👨‍💻 Author  
🌍 Location: Nepal 🇳🇵  

---

🌟 **If you found this project useful, give it a star!** 🌟  

