# Image Processing Techniques 📸

This repository contains various **image processing techniques** implemented using **OpenCV** and **NumPy** in Python. 

##  Features Implemented

### **1 Loading and Displaying Images**
- Load an image using `cv2.imread()`
- Resize and display using `cv2.imshow()` (Colab users should use `cv2_imshow()`)

### **2 Color Channel Analysis**
- Extract and display **Red, Green, and Blue (RGB)** channels separately.
- Convert RGB channels to grayscale for analysis.

### **2 Arithmetic Operations on Images**
- **Addition & Subtraction** → Adjust brightness by adding/subtracting pixel values.
- **Multiplication & Inversion** → Change contrast and invert colors.

### **4 Contrast Enhancement Techniques**
- **Contrast Stretching** → Expands pixel intensity range for better visibility.
- **Gamma Correction** → Adjusts image brightness non-linearly.
- **Logarithmic Transformation** → Enhances dark areas while preserving highlights.

### **5 Intensity Transformations**
- **Intensity-Level Slicing** → Highlights a specific range of pixel values.
- **Bit-Plane Slicing (Not Implemented Yet)** → Extracts different bit levels from an image.

---

##  How to Use
1. Open the notebook in **Google Colab**:
   - [![Open In Colab](https://colab.research.google.com/github/ranaehelal/Contrast-Enhancement/blob/main/jellyfish_analysis.ipynb)
   
2. Upload an image (`jellyfish.jpg` or `stretch_original.webp`) to the Colab environment.

3. Run the cells to apply different **image processing techniques**.

---

## 📌 Dependencies
Make sure you have the following libraries installed:
```python
!pip install opencv-python matplotlib numpy
