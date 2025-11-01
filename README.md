# Traffic Sign Image Classification using CNN

## 1. Introduction

This project implements a **Convolutional Neural Network (CNN)** model using the **TensorFlow/Keras** library to automatically classify various types of traffic signs from images. The model was successfully trained and achieved an **impressive accuracy of 96%** on the test dataset, demonstrating superior traffic sign recognition capabilities.

## 2. Key Features

* **Data Preprocessing:** Loading, cleaning, and normalizing traffic sign image data.
* **Model Construction:** Designing a multi-layered CNN architecture optimized for image classification tasks.
* **High Performance:** Achieved a **96% accuracy** in classifying traffic signs.
* **Training:** Training the CNN model on the prepared dataset.
* **Evaluation & Prediction:** Assessing performance and making predictions on new traffic sign images.

## 3. Technologies Used

* **Language:** Python
* **Deep Learning:** `TensorFlow` / `Keras`
* **Data Handling:** `NumPy`, `Pandas`
* **Image Processing:** `OpenCV (cv2)`, `PIL (Pillow)`
* **Environment:** Jupyter Notebook (`.ipynb`)

## 4. Setup and Installation

To run this project, you need to install the following Python libraries:

1.  **Clone Repository:**
    ```bash
    git clone <YOUR_REPO_ADDRESS>
    cd <REPO_NAME>
    ```

2.  **Install Libraries:**
    Use `pip` to install the necessary dependencies.
    ```bash
    pip install numpy pandas tensorflow keras opencv-python pillow jupyter
    ```
    *Note: You may need to use `pip install opencv-python-headless` if you encounter display issues on some operating systems.*

## 5. Usage Guide

1.  **Download Data:** Ensure you have downloaded the traffic sign image dataset (e.g., GTSRB) and placed it in the correct directory required by the notebook (usually `/data` or similar).
2.  **Open Notebook:** Open the `traffic-sign-image-classification-cnn.ipynb` file using Jupyter Notebook or JupyterLab.
    ```bash
    jupyter notebook traffic-sign-image-classification-cnn.ipynb
    ```
3.  **Run Code:** Execute the cells in the notebook sequentially. The notebook will automatically load the data, build the model, train it, and evaluate the results.
