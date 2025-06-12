# MealLens-Inc.
The Dataset Development &amp; Annotation Tool project at MealLens aims to create a scalable and efficient system for collecting, labelling, and organizing food ingredient images. This tool will enable the development of a high-quality dataset essential for training AI models that identify food items and extract nutritional insights.

# 🍽️ Food Image Segmentation using SAM2

This project demonstrates how to perform **automatic image segmentation** using the **SAM2 (Segment Anything Model 2)** framework by Meta AI, specifically designed to identify multiple segmented regions in images (e.g., food dishes). It is optimized for batch processing and can visualize the segmented masks overlayed on the original image.

---

## 🚀 Features

- Loads and builds the SAM2 model using a custom YAML configuration and checkpoint.
- Automatically detects and segments multiple objects in images.
- Supports batch processing from a folder of images.
- Displays a sample segmented output using `matplotlib`.
- Fully compatible with CPU and GPU devices.

---

## 🛠️ Requirements

- Python 3.8+
- PyTorch (with GPU support recommended)
- OpenCV
- Matplotlib
- NumPy
- SAM2 repository installed (via `pip install -e .[notebooks]`)

---

## 📁 Project Structure

├── sam2_segmentation.py # Main script to run segmentation

├── checkpoints/ # Directory containing .pt SAM2 model files

├── sam2/ # Cloned Segment Anything v2 repo

├── food_images_sample/ # Folder containing food images


