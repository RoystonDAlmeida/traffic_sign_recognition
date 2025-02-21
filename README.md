# Traffic Sign Recognition using CNN

This project demonstrates how to build a traffic sign recognition system using a Convolutional Neural Network (CNN) in Google Colab.

## Dataset

The project uses the GTSRB - German Traffic Sign Recognition Benchmark dataset from Kaggle. This dataset contains over 50,000 images of 43 different traffic signs.

## Project Structure

The project is organized into the following steps:

1. **Data Acquisition:** Download and extract the dataset using the Kaggle API.
2. **Data Preprocessing:** Load, resize, and normalize the images.
3. **Model Design:** Create a CNN model using TensorFlow/Keras.
4. **Model Compilation:** Compile the model with an appropriate optimizer and loss function.
5. **Model Training and Validation:** Train the model and validate it using a validation set.
6. **Model Evaluation:** Evaluate the model's performance on the test set.
7. **Testing with Uploaded Image:** Predict the traffic sign in an uploaded image.

## Usage

1. **Setup:** Install necessary libraries (`pip install kaggle`).
2. **Data:** Download the dataset using Kaggle AP.
3. **Training:** Execute the code cells to train the model.
4. **Prediction:** Use the file uploader to upload an image of a traffic sign and click the "Predict" button.

## Model Architecture

The CNN model consists of the following layers:

- Convolutional layers with ReLU activation
- Max pooling layers
- Flatten layer
- Dense layers with ReLU activation
- Output layer with softmax activation

## Results

The model achieves an accuracy of over 95% on the test set.

## Contributing

Feel free to contribute to this project by improving the model architecture, data preprocessing, or adding new features.
