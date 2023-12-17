# UNet Model for Image Segmentation

This repository contains an implementation of a UNet model for image segmentation, with a focus on flexibility and ease of use for various datasets. The architecture utilizes a series of convolutional layers with channel sizes (16, 32, 64, 128, 256, 512) to capture hierarchical features.

## Features

- **UNet Architecture:** The core of the repository is the UNet model, a proven architecture for image segmentation tasks.
  
- **Monai Integration:** The implementation is built on top of MONAI, a PyTorch-based framework designed for medical image analysis. Despite its origins, the model is adaptable for various image segmentation applications beyond biomedical images.

- **Test and Train Loops:** The repository includes well-defined test and train loops, providing a structured framework for training and evaluating the UNet model.

- **MetricsEvaluator Class:** A MetricsEvaluator class is implemented to facilitate the incorporation of different metrics for evaluating model performance. This class enhances the flexibility of the evaluation process.

- **Customizable for Different Datasets:** The UNet model is designed to be easily customizable for different datasets. You can adapt the architecture and parameters to suit the specific characteristics of your data.

- **Dataset Information:** The dataset utilized in the provided example consists of 512x512 images. The segmentation mask is represented with values 0 and 1, corresponding to background and foreground, respectively.


Feel free to explore and modify the code to meet your specific requirements. Contributions and feedback are welcome!
