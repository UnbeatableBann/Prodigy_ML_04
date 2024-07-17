# Hand Gesture Recognition Model Using LeapGestRecog Dataset

This repository contains a project that implements a hand gesture recognition model using the LeapGestRecog dataset. The model accurately identifies and classifies different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Hand gesture recognition is a vital technology in computer vision applications, enabling natural and intuitive interaction with devices. This project focuses on developing a machine learning model that can classify hand gestures accurately using the LeapGestRecog dataset. The model can be integrated into various applications such as virtual reality, robotics, and smart devices.

## Dataset

The dataset used in this project is the LeapGestRecog dataset, available on Kaggle. It contains images of hand gestures captured using the Leap Motion controller. Each gesture is associated with a specific class label, making it suitable for training and evaluating machine learning models for gesture recognition tasks.

To download the dataset using the Kaggle API:

1. Ensure you have the Kaggle API installed. If not, you can install it using:
    ```bash
    pip install kaggle
    ```

2. Authenticate the Kaggle API by placing your `kaggle.json` API token in the appropriate directory (Use your username):
    - On Windows: `C:\Users\<YourUsername>\.kaggle\kaggle.json`
    - On Mac/Linux: `~/.kaggle/kaggle.json`

3. Download the dataset:
    ```bash
    !kaggle datasets download -d gti-upm/leapgestrecog
    ```

4. Extract the downloaded dataset into the `data` directory of the project.

## Installation

To run this project locally, you need to have Python installed along with the necessary libraries. Follow these steps to set up the environment:

1. Clone this repository:
    ```bash
    git clone https://github.com/UnbeatableBann/hand-gesture-recognition.git
    cd hand-gesture-recognition
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare the dataset:
    - Ensure the dataset is downloaded from Kaggle and extracted into the `data` directory of the project.

2. Run the Jupyter Notebook or Python scripts provided:
    ```bash
    jupyter notebook hand_gesture_recognition.ipynb
    ```

3. Follow the steps in the notebook or scripts to preprocess the data, train the model, and evaluate its performance.

## Results

The project outputs the accuracy and performance metrics of the hand gesture recognition model. It also includes visualizations or examples of correctly classified gestures, demonstrating the model's effectiveness.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.
