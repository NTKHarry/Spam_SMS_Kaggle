# SMS Spam Detection using Simple LSTM

## Project Description

This project utilizes a simple LSTM (Long Short-Term Memory) model to classify SMS messages into two categories: "Spam" and "Ham" (non-spam). The dataset used is the [Kaggle SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

## Dataset

- **Source**: [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Description**: This dataset contains SMS messages that are labeled as either "ham" (non-spam) or "spam". It is widely used for training spam classification models.

## Model

The model used in this project is a **Simple LSTM (Long Short-Term Memory)** network, which is effective for sequential data like text. The LSTM architecture was selected to capture the temporal dependencies in SMS text data for spam classification.

## How to Run the Code

1. Clone the repository:
    ```bash
    git clone https://github.com/NTKHarry/Spam_SMS_Kaggle.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Results

The model achieves decent performance in classifying SMS messages into "spam" and "ham" categories. The results can be visualized in the form of loss and accuracy graphs, and the confusion matrix.

## Acknowledgements

- Dataset: [Kaggle SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Model: Simple LSTM
