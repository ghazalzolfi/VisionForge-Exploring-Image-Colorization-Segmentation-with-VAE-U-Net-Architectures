
# Image Colorization and Segmentation with VAEs and U-Net

This repository provides practical implementations of two advanced machine learning techniques: image colorization using Variational Autoencoders (VAEs) and image segmentation using the U-Net architecture. It covers preprocessing, model training, evaluation, and analysis, offering practical insights into generative modeling and segmentation techniques widely used in computer vision.

### Project Overview:

### **1. Image Colorization using Variational Autoencoders (VAEs)**:
- **Objective**: Convert grayscale images into realistic colored versions.
- **Methodology**:
  - Implemented a Variational Autoencoder (VAE), leveraging an encoder-decoder structure to learn latent representations of color distributions.
  - Enhanced model performance with perceptual loss and feature extraction from pre-trained convolutional neural networks.
  - Evaluated model outputs using visual and quantitative metrics to measure colorization quality.

### **2. Image Segmentation using U-Net**:
- **Objective**: Perform precise image segmentation to accurately classify each pixel within an image.
- **Methodology**:
  - Implemented the U-Net architecture, specifically designed for biomedical image segmentation but versatile enough for general-purpose image segmentation tasks.
  - Explored data augmentation techniques to enhance the training dataset, improving model robustness.
  - Conducted detailed evaluation and comparison using segmentation metrics such as Intersection-over-Union (IoU) and Dice coefficient.

### Key Learning Outcomes:
- Developed deep understanding and hands-on skills with generative models (VAEs) and segmentation architectures (U-Net).
- Gained proficiency in dataset preprocessing, feature extraction, and augmentation techniques.
- Acquired insights into analyzing and visualizing model performance for practical computer vision tasks.

### Libraries and Tools:
- Python
- PyTorch (model implementation and training)
- PyTorch Lightning (efficient model training)
- NumPy, Pandas (data handling)
- Matplotlib, Seaborn (visualizations)
- sklearn (preprocessing and evaluation)

This project offers foundational and practical knowledge in applying advanced generative and segmentation techniques, emphasizing their real-world applicability and industry relevance.
