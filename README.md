# CBIR Feature Extraction Project

This project implements Content-Based Image Retrieval (CBIR) using three feature extraction techniques:
- Zernike Moments(Best performance)
- Hu Moments
- Fourier Descriptors

## Dataset
- Total Images: 400  
- Classes: 20  
- Images per Class: 20  
- Preprocessing: Resized & Intensity Normalized (0-255)

## Performance Results
| Feature Extraction Method | Precision | Recall |
|--------------------------|-----------|--------|
| Zernike Moments | 69.4 | 67.7 |
| Hu Moments | 0.4759 | 0.6899 |
| Fourier Descriptors | 0.5766 | 0.6685 |

##  How to Use
1. Download the `.ipynb` files.
2. Open them in **Google Colab** or **Jupyter Notebook**.
3. Run each notebook to extract features and retrieve images.

##  GUI for CBIR
- A **Graphical User Interface (GUI)** is implemented in the **Zernike Moments notebook**.
- It allows users to input an image and retrieve similar images from the dataset.
- Run the last section of the **zernike_feature_extraction.ipynb** notebook to use the GUI.

##  Author
- Zoobiya Aalam
- aalam.zoobiya@gmail.com
- https://www.linkedin.com/in/zoobiya-aalam-28621724a/?originalSubdomain=pk
