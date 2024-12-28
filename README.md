# Colon Cancer Image Analysis Using U-Net

---

## **Project Overview**

This project uses a **U-Net deep learning model** which is a convolutional neural network (CNN) specifically designed for image segmentation tasks. A simpler generic CNN is used in this case for cell counting without segmentation to analyze HT29 colon cancer images, focusing on predicting cell counts. The goal is to simplify and automate the process of counting cells, which is often done manually, and help improve accuracy and efficiency in biomedical research.

---

## **Key Features**

- **U-Net Model**: A well-known architecture designed for segmentation tasks, adapted here for cell count predictions.  
- **Performance Tracking**: Includes **Mean Absolute Error (MAE)** and **loss metrics** to evaluate accuracy.  
- **Validation**: Compares predictions with manual counts to ensure reliability.  
- **Reproducible Notebook**: The implementation is provided in a Colab notebook, making it easy to follow and replicate.

---

## **Results at a Glance**

- **Training Loss**: 1042.12  
- **MAE**: 29.09  

Example validation results:  
- Image: `A03f00d0.tif`  
  - Manual Count: **356**  
  - Predicted Count: **371.10**  
- Image: `A03f01d0.tif`  
  - Manual Count: **339**  
  - Predicted Count: **382.08**  

While the predictions are reasonably close, there’s room for improvement in refining the model.

---

## **Folder Structure**
