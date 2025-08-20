# 🌋 Landslide Detection using U-Net (PyTorch)

## 📌 Project Overview
This project implements a *deep learning-based Landslide Detection system* using the *U-Net architecture* in PyTorch.  
It performs *semantic segmentation* on satellite imagery to identify landslide-affected regions, aiding in disaster risk assessment and mitigation planning.  

The model was trained on annotated satellite images and evaluated using Intersection over Union (IoU) and Dice Score metrics.  
*Trained Model Achievements*:  
- Average IoU: *0.1950*  
- Average Dice Score: *0.2728*  

---

## 🚀 Features
- *Semantic Segmentation* for detecting landslide regions from satellite images.
- *U-Net Architecture* for accurate pixel-wise segmentation.
- *GPU Acceleration* with CUDA for faster training.
- *Evaluation Metrics*: IoU and Dice Score.
- *Data Preprocessing*: image resizing, normalization, and tensor conversion.

---

## 🛠 Tech Stack
- *Programming Language*: Python 3.x
- *Framework*: PyTorch
- *Model Architecture*: U-Net
- *Training Environment*: Google Colab (GPU)
- *Visualization*: Matplotlib, Pillow
- *Version Control*: Git & GitHub

---

## 📂 Project Structure
📦 Landslide-Detection
1. ┣ 📂 data/
  -  Dataset (images & masks)
2. ┣ 📂 outputs/
  - Predicted masks & sample results
3. ┣ 📜 model.py
  - U-Net model implementation
4. ┣ 📜 train.py
  -  Training loop
5. ┣ 📜 utils.py             
  - Helper functions
6. ┣ 📜 predict.py
  - Inference script
7. ┣ 📜 main.ipynb
  - Colab notebook for training & inference
8. ┣ 📜 requirements.txt
  - . Python dependencies
9. ┗ 📜 README.md
  - Project documentation


---

## Results
-	*Average IoU*: 0.1950
-	*Average Dice Score*: 0.2728

---
## Author
- Shaswat Raj
- 📧 Email: shaswatraj536@gmail.com
- 🔗 GitHub: https://github.com/rajShaswat005
- 💼 LinkedIn: https://www.linkedin.com/in/shaswat-raj-8b9487260/
