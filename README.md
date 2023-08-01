# RSNA-Breast-Cancer-Detection-Pytorch

# Breast Cancer Detection with Screening Mammograms

![Breast Cancer](https://user-images.githubusercontent.com/12345678/your-image.png)

## Introduction

This repository contains the code and data for the "Breast Cancer Detection with Screening Mammograms" competition. The goal of this competition is to identify breast cancer from screening mammograms using machine learning techniques. Early detection of breast cancer is critical for reducing cancer fatalities, and this project aims to improve the accuracy and efficiency of breast cancer detection in regular screening.

The competition was hosted by the Radiological Society of North America (RSNA), a non-profit organization promoting excellence in patient care and health care delivery through education, research, and technological innovation.

## About Breast Cancer

Breast cancer is the most commonly occurring cancer worldwide, with millions of new diagnoses and hundreds of thousands of deaths each year. Regular mammography screening has significantly reduced breast cancer mortality in high-income countries. However, the reliance on highly-trained human observers makes screening programs expensive and prone to false positive results, leading to unnecessary follow-ups and anxiety for patients.

## Dataset

The dataset used in this competition consists of screening mammograms obtained from regular screening. Each mammogram is labeled with the presence or absence of breast cancer.

## Project Structure

The project is organized as follows:

- `data`: This directory contains the dataset used for training and validation.
- `models`: This directory contains the implementation of different models used for breast cancer detection.
- `utils`: This directory contains common utility functions used in training and evaluation.
- `train.ipynb`: Jupyter Notebook for training the models and evaluating their performance.
- `inference.ipynb`: Jupyter Notebook for making predictions on new mammograms using the trained models.

## Dependencies

To run the code in this repository, you will need the following dependencies:

- Python 3.8+
- PyTorch 1.8+
- torchvision 0.9+
- pandas
- scikit-learn
- matplotlib

You can install the required packages using the following command:

```
pip install -r requirements.txt
```

## Getting Started

To get started, follow the steps below:

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/breast-cancer-detection.git
```

2. Navigate to the project directory:

```
cd breast-cancer-detection
```

3. Download the dataset and place it in the `data` directory.

4. Run the Jupyter Notebook `train.ipynb` to train the models and evaluate their performance.

5. Use the trained models to make predictions on new mammograms by running the `inference.ipynb` notebook.

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug fixes, or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

We would like to thank the Radiological Society of North America (RSNA) for hosting this competition and providing the dataset for research and development. Our work is built upon the efforts of the RSNA and the valuable contributions of the participants in the competition.
