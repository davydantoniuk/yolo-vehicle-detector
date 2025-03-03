# **Vehicle Detection Using YOLOv8**

https://davydantoniuk.github.io/yolo-vehicle-detector/

This project implements **YOLOv8** for vehicle detection using the **KITTI dataset**. The dataset was **preprocessed, balanced, and augmented** to improve model performance. The model was trained on a **custom dataset**, achieving **mAP@50: 0.834**.

## **Project Structure**

-   **Dataset Preparation**: KITTI dataset preprocessing and conversion to YOLO format.
-   **Data Balancing**: Downsampling, oversampling, and synthetic data generation.
-   **Model Training**: YOLOv8 training with optimized hyperparameters.
-   **Evaluation**: Performance metrics including confusion matrix, PR curves, and loss analysis.
