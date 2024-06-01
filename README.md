# Breast Cancer Classification using Deep Learning from Ultrasound Images

This repository contains code for a deep learning model to classify breast cancer from ultrasound images. The model is implemented in Python using Google Colaboratory, and it utilizes convolutional neural networks (CNNs) for image classification.

To run the model, please follow the instructions below:

## Prerequisites
- Google Colaboratory account (free)
- Dataset: "Dataset_BUSI_with_GT"
  - The dataset should be located in your Google Drive at the path: "/content/drive/MyDrive/project/Dataset_BUSI_with_GT/"

## Steps to Run the Model

1. Go to [Google Colaboratory](https://colab.research.google.com/).
2. Select the model code file from your desired location.
3. In the Colaboratory, go to the "Runtime" tab and select "Run all" to execute the entire code.
4. The system will ask for permission to access your Google Drive. It is important to allow access to load the dataset.
5. The model will start training and may take some time to complete.
6. Once training is finished, the images of the model visualization will be exported to your Google Drive at the path: "/content/drive/MyDrive/project/outputs/"
7. The model result metrics will be printed at the end of the code execution.

Please note that the model training time may vary depending on the size of the dataset and your hardware resources.

## Additional Information

- The code is implemented in Python, utilizing libraries such as TensorFlow and Keras for deep learning.
- The model architecture is based on convolutional neural networks (CNNs), which are commonly used for image classification tasks.
- The dataset "Dataset_BUSI_with_GT" should contain ultrasound images of breast tissue along with corresponding ground truth labels.
- The model will output evaluation metrics to assess its performance in classifying breast cancer.
- Feel free to explore and modify the code to experiment with different model architectures or datasets.

## Disclaimer

This model is provided for educational and research purposes only. It is not intended for clinical use or as a substitute for professional medical advice. Always consult with a qualified healthcare professional for accurate diagnosis and treatment options.
