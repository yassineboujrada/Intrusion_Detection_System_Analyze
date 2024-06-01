# Intrusion Detection System (IDS) Project

This project aims to develop an Intrusion Detection System (IDS) 🕵️‍♂️🕵️‍♂️ using deep learning techniques. The IDS model is designed to detect malicious activities and potential threats within a network by analyzing traffic data.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Intrusion Detection System (IDS) project utilizes machine learning techniques to identify and prevent potential security threats. This project demonstrates the implementation of a deep learning model for detecting various types of network intrusions.

## Features

- Detects a wide range of network intrusions.
- Utilizes deep learning for high accuracy in threat detection.
- Provides a framework for training, evaluating, and deploying the IDS model.
- Easy-to-use interface for interacting with the system.

## Installation

To get started with the IDS project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yassineboujrada/Intrusion_Detection_System_Analyze.git
    ```
    ```bash
    cd Intrusion_Detection_System_Analyze
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    ```
    ```bash
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Model Training

The training process for the IDS model involves the following steps:

1. **Data Preparation**: Prepare a dataset containing network traffic data with labeled instances of normal and malicious activities.
   
2. **Model Training**: Train the deep learning model using the prepared dataset. The training process involves adjusting the model's parameters to accurately classify normal and malicious activities.

3. **Model Evaluation**: Evaluate the model's performance using validation data to ensure it accurately detects intrusions.

The notebook `IDS.ipynb` contains detailed code and explanations for each of these steps.

## Results

The trained model's performance is evaluated based on accuracy and validation accuracy. The following plot shows the training and validation accuracy over epochs:

![Accuracy Plot](https://github.com/yassineboujrada/Intrusion_Detection_System_Analyze/blob/main/docs/accuracy_plot.png)

and for evaluation of every algorithm of classification used in this project :

![Evalution](https://github.com/yassineboujrada/Intrusion_Detection_System_Analyze/blob/main/docs/evaluation.png)

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or open an issue. 😉

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 💪✌️
