# Pneumonia-Detection-Project
Medical imaging and artificial intelligence (AI) are revolutionizing healthcare. Pneumonia, a serious lung infection, is typically diagnosed using chest X-rays. However, manual interpretation of these images can be time-consuming and prone to errors. By leveraging deep learning and computer vision, this project aims to enhance pneumonia diagnosis.

## Problem Statement
The task is to build an AI model capable of detecting lung opacities (a key symptom of pneumonia)
from medical images. The model should:

• Identify pneumonia cases based on chest X-ray images.
• Locate lung opacities by drawing bounding boxes on affected regions.
• Classify images into categories based on the presence of pneumonia.

Context
• Medical images are stored in DICOM format (*.dcm), which contain metadata and pixel data.
• The dataset contains annotated images with bounding boxes that mark pneumonia regions.
• Some images may have abnormalities but no pneumonia, making classification more challenging.

Dataset Information
The dataset used in this project comes from the RSNA Pneumonia Detection Challenge and consists of:
• Chest X-ray images in DICOM format.
• Labels for each image, including:
o Pneumonia positive cases (with bounding boxes).
o No pneumonia cases (either normal or with other lung abnormalities).

## Objective
Design a Deep Learning model that:
Classifies chest X-rays as "Pneumonia" or "No Pneumonia".
Detects and localizes pneumonia-affected areas in the images.

