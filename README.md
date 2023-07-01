# Resistor Detector with Machine Learning

This repository contains the code necessary to train and utilize a Convolutional Neural Network (CNN) for resistor recognition from images. The trained model classifies 37 different resistor types with high accuracy. It is then used to detect and classify resistors in new, unseen images.

The project uses Python and Keras on top of TensorFlow, and it can be run entirely in Google Colab.

## Repository Structure

* **Model_Training.ipynb**: Jupyter notebook that contains the code to train the CNN. The trained model is then saved for later use.

* **Resistor_Detector.ipynb**: Jupyter notebook that loads the trained model and uses it to classify resistors in new images.

* **resistor_model.h5**: The saved trained model. This can be loaded in the Testing notebook to make predictions without having to retraining the model.

## How to Use

### Training

1. Open the Model_Training notebook in Google Colab.
2. Run the cells to download and prepare the dataset. The dataset is split into a training set and a testing set.
3. Run the cells to define and train the CNN. The model's architecture and training parameters can be adjusted as needed.
4. Save the trained model to disk. This model can later be loaded to make predictions without having to retrain.

### Testing

1. Open the Testing notebook in Google Colab.
2. Run the cell to upload your test image. The image should contain one or more resistors that you want to classify.
3. Run the cells to load the trained model and use it to classify the resistors in your image.

## Customizing the Model

The architecture and training parameters of the CNN can be customized to better suit your needs. This can include changing the number of layers, the number of neurons in each layer, the activation functions, the optimizer, the loss function, the batch size, and the number of epochs.

Keep in mind that changing these parameters may affect the performance of the model. It is recommended to understand how these parameters work and to experiment with different values to see what works best for your specific use case.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. All contributions are welcome!
