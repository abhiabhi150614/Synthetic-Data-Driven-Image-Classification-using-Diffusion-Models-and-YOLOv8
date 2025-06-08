# Synthetic-Data-Driven-Image-Classification-using-Diffusion-Models-and-YOLOv8(https://colab.research.google.com/drive/182rPdgFVRTGufCwHQO4ILJKd4EkCht9s?usp=sharing)

This project demonstrates an end-to-end machine learning pipeline for image classification, addressing the challenge of data scarcity by leveraging generative AI. It utilizes a combination of Google's Gemini API for diverse prompt generation and Stable Diffusion for synthetic image creation to build a custom dataset. This synthetic data is then used to train a YOLOv8 model for classifying images into predefined categories.

**Key Features:**

*   **Synthetic Data Generation:** Automatically generates a custom dataset of images using Stable Diffusion, guided by diverse prompts obtained from the Gemini API.
*   **YOLOv8 Training:** Trains a YOLOv8 model on the generated synthetic data for image classification.
*   **Dataset Preparation:** Includes scripts for splitting the dataset and generating YOLOv8-compatible labels.
*   **Model Inference:** Provides code for loading the trained model and performing inference on new images.

**Technologies Used:**

*   Python
*   Google Colab
*   Google Gemini API
*   Stable Diffusion (via `diffusers` library)
*   YOLOv8 (via `ultralytics` library)
*   PyTorch
*   OpenCV
*   Matplotlib

**Project Structure:**

*   `[Code cells in notebook]`: Contains the code for data generation, dataset preparation, model training, and inference.
*   `dataset_s/`: Directory for storing the initially generated synthetic images.
*   `dataset/`: Directory for storing the processed dataset in YOLOv8 format (images and labels).
*   `dataset.yaml`: YOLOv8 dataset configuration file.
*   `best (3).pt`: Example of a trained model weight file.

**How to Run:**

1.  Open the notebook in Google Colab.
2.  Ensure you have the necessary API keys for Google Gemini (replace the placeholder).
3.  Run the code cells sequentially to generate data, train the model, and perform inference.

This project showcases the potential of using generative AI to augment datasets and train robust computer vision models, particularly in scenarios where real-world data collection is challenging or expensive.
