
# DeepLearningProjects

This repository contains several deep learning projects, each designed to tackle specific tasks like image classification, object detection, and text generation. All projects are implemented using Jupyter notebooks and were developed on Google Colab.

## Projects Overview

### 1. Image Classification
This folder includes projects related to image classification, focusing on tasks such as detecting pollen on bees and identifying brain tumors.

- **Bee with Pollen Detection**:  
  - `pollen_my_model.ipynb`: Custom model for detecting pollen on bees.
  - `pollen_with_MobileNet.ipynb`: Pollen detection model using MobileNet architecture.
  - `pollen_with_VGG19.ipynb`: Pollen detection model based on the VGG19 architecture.

- **Brain Tumor Detection**:  
  - `brain_tumor_with_VGG19.ipynb`: Brain tumor detection model utilizing VGG19.
  - `brain_tumor_my_model.ipynb`: Custom model for detecting brain tumors.

### 2. Object Detection (YOLO_V5)
This folder contains a project for object detection using the YOLO_V5 model, trained on a custom dataset to identify objects such as balls and people. This can be useful in applications like sports analysis, security, and other contexts where identifying these objects is essential.

- `TRAIN_YOLO_V5_ON_YOUR_CUSTOM_DATASET.ipynb`: Notebook for training the YOLO_V5 model on a custom dataset. The model is configured to detect objects including **balls** and **people** in various scenarios.

### 3. Text Generation
This folder includes projects focused on generating text using different recurrent neural network (RNN) architectures.

- `Text_Generation_using_LSTMs.ipynb`: Text generation model using Long Short-Term Memory (LSTM) networks.
- `text_generation_with_RNN.ipynb`: Text generation model based on a standard Recurrent Neural Network (RNN) architecture.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DeepLearningProjects.git
   ```
2. Open the desired notebook in Google Colab.


## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: TensorFlow, Keras, OpenCV, and other libraries as specified in each notebook.

## License
This repository is open-source and available under the MIT License.
