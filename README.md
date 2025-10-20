# 🧩 Image Segmentation using K-Means Clustering

This project demonstrates **image segmentation** using the **K-Means clustering algorithm**, implemented with **OpenCV** and **scikit-learn**.  
The notebook showcases how unsupervised learning can be applied to separate regions in an image based on color similarity.

---

## 📘 Overview

The notebook performs the following steps:

1. Loads an input image  
2. Reshapes the image into a 2D array of pixels  
3. Applies **K-Means clustering** to group similar pixels  
4. Reconstructs the segmented image using the cluster centers  
5. Displays both the **original** and **segmented** images side by side

---

## ⚙️ Features

- 🎯 **K-Means clustering** for color-based segmentation  
- 🧠 **OpenCV integration** for image handling and preprocessing  
- 📊 **Matplotlib visualization** for side-by-side comparison  
- ⚙️ **Customizable parameters** for number of clusters and convergence criteria

---

## 🚀 Usage

1. Place your input image in the working directory as `images.jpeg`  
2. Open and run all cells in the notebook  
3. Adjust the `k` parameter to control the number of color segments  
4. View the comparison between the original and segmented images  

---

## 🔧 Parameters

| Parameter | Description |
|------------|-------------|
| `k = 5` | Number of clusters (segments) |
| `criteria = (cv2.TERM_CRITERIA_EPS + cv2.TERM_CRITERIA_MAX_ITER, 100, 0.2)` | Stopping criteria for K-Means |
| `attempts = 10` | Number of times the algorithm runs with different initializations |
| `flags = cv2.KMEANS_PP_CENTERS` | Initialization method for cluster centers |

---

## 🖼️ Results

The notebook outputs two images:
- **Original Image:** The unaltered input  
- **Segmented Image:** The color-reduced output reconstructed from `k` clusters  

This demonstrates how K-Means effectively groups similar colors, producing visually distinct segments.

---

## 💡 Applications

- Image compression  
- Object detection preprocessing  
- Computer vision pipelines  
- Image analysis and understanding  

---

## 🧠 Technologies Used

- Python  
- OpenCV  
- scikit-learn  
- NumPy  
- Matplotlib  

---

## 👤 Author

**Mohamed Galal**  
📍 Cairo University, B.Sc. in Computer Science  
💼 AI Engineer | Python | Computer Vision | NLP  
🔗 [GitHub](https://github.com/galall10) • [LinkedIn](https://linkedin.com/in/mohamedgalal10)
