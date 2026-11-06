# Face Mask Detection with SOTA CV & Demo (Assignment 2)

Project repository for Astana IT University, Computer Vision course.

## Team Members
* Bibifatima
* Aldiyar Amangaliyev (SE-2403)
* Chingiz

## Project Overview
This project upgrades our Assignment 1 face mask classification system by integrating State-of-the-Art (SOTA) components:
* **Binary Classification & Ablation Study:** MobileNetV2 trained with and without data augmentations (flip, brightness, rotation) using a combined dataset (Kaggle + personal + synthetic data).
* **MedSAM2 Segmentation:** Zero-shot spatial localization and explainability of face masks with IoU and Dice metrics evaluation.
* **PSA Explainer Clip Generation:** Talking-head video generation using a VASA-1/SadTalker concept with mandatory watermarking for ethical synthetic media demonstration.
* **Interactive Web App:** Deployed via Gradio for real-time inference, video generation, and metric tracking.

## Repository Structure
* `Assignment_2_Face_Mask_Detection.ipynb` - Main Google Colab notebook containing data pipelines, training, ablation study, MedSAM2, and Gradio app deployment.
* `README.md` - Project documentation.

## How to Run
1. Open the `.ipynb` notebook in Google Colab with GPU runtime enabled (T4).
2. Run cells sequentially to load the dataset, execute training and ablation experiments, generate segmentation masks, and launch the Gradio web application interface.
