# Handwritten Digits Recognition

## Introduction
This project demonstrates the training and evaluation of a Convolutional Neural Network (CNN) model for recognizing handwritten digits. The model is trained using the MNIST dataset, and its performance is evaluated using both the MNIST test dataset and custom handwritten digit images.

## Features
- Training a CNN model using the MNIST dataset
- Evaluating the model's performance on MNIST test data
- Testing the model with custom handwritten digit images
- Displaying evaluation metrics such as precision, recall, and F2 score
- Visualizing the confusion matrix to understand model predictions

## Installation
1. Clone the repository:
 ```
 git clone https://github.com/your_username/handwritten-digits-recognition.git
 ```

2. Install the required Python packages:

```
pip install -r requirements.tx
```
3. Download the test_data file from google drive:
**Google Drive link:** [test_data](https://drive.google.com/drive/folders/1baxlrtmERe5FPhdQWj-W-k8tBvmvRjrN).


## Usage
1. Run the Jupyter notebook `main.ipynb` to train the model and evaluate its performance.
2. To test the model with custom handwritten digit images, place the images in the `test_data` directory.
3. Run the notebook cell for testing the model with custom images.

## Files
- `main.ipynb`: Jupyter notebook containing code for training, evaluating, and testing the CNN model.
- `test_data/`: Directory containing custom handwritten digit images for testing the model.
- `my_model.h5`: Saved trained model file.

## Results
- The model's training and validation accuracy/loss curves are plotted.
- Evaluation metrics such as precision, recall, and F2 score are calculated and displayed.
- A confusion matrix is visualized to understand the model's predictions on both MNIST test data and custom images.

## Conclusion
The CNN model demonstrates decent performance in recognizing handwritten digits. Further improvements can be made by optimizing hyperparameters, increasing training data, or exploring more complex architectures.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




