# 👗 Fashion Image Similarity Recommendation System

This project is an AI-based application that recommends visually similar fashion items when a user uploads an image. It uses **Deep Learning (ResNet50)** for feature extraction and **KNN** for similarity matching. A simple and interactive **Streamlit** interface is used to display the results.

---

## 🌟 Features

### 🔍 Smart Image Recommendations
- Upload any fashion product image.
- Get the top 5 similar fashion items.
- Accurate deep-feature matching.

### 🧠 Deep Learning Feature Extraction
- Built using **ResNet50 pretrained on ImageNet**.
- Extracts 2048-dimensional feature vectors.
- Captures style, color, texture, and pattern.

### 🧮 Fast Similarity Search
- Uses **KNN with Euclidean distance**.
- Precomputed features ensure quick responses.
- Stored embeddings in `.pkl` files.

### 💻 Streamlit Web Interface
- User-friendly front-end.
- Image upload preview.
- Organized 5-column recommendation layout.

---

## 📁 Dataset

This system uses the **Fashion Product Images (Small)** dataset.

🔗 Kaggle Dataset:  
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

The dataset contains:
- 44,000+ fashion item images  
- Multiple categories  
- High-resolution images  
- Metadata (`styles.csv`)



