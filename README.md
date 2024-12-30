# MNIST Digit Recognition with TensorFlow

This project demonstrates a digit recognition model using the MNIST dataset and TensorFlow. The model trains on the MNIST dataset of handwritten digits (0-9) and evaluates its performance. Additionally, it visualizes the results using Matplotlib.

## Features

- **Model**: Built using TensorFlow and Keras.
- **Dataset**: Utilizes the MNIST dataset of handwritten digits.
- **Visualization**: Visualizes predictions and training metrics using Matplotlib.

## Requirements

Before running the project, ensure you have the following installed:

- Python 3.x
- TensorFlow
- Matplotlib
- NumPy
- Jupyter Notebook (optional, for interactive use)

Install the required packages using pip:

```bash
pip install tensorflow matplotlib numpy
```

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/smolvamp/MNIST-based-digit-recognition/ 
   cd MNIST-based-digit-recognition
   ```

2. Run the train_model.ipynb:

   ```bash
   jupyter nbconvert --execute train_model.ipynb
   ```

3. View the visualization graphs and model predictions by running the test_model.ipynb:
   ```bash
   jupyter nbconvert --execute test_model.ipynb
   ```

## Dataset

The MNIST dataset is automatically downloaded using TensorFlow's `keras.datasets` module. It consists of:

- 60,000 training images
- 10,000 testing images

Each image is a 28x28 grayscale pixel representation of a digit.

## Results

- Training accuracy: ~99%
- Testing accuracy: ~98%

### Sample Visualization

- **Loss/Accuracy Plots**: Training and validation metrics.
- **Sample Predictions**: Displayed with true and predicted labels.

## Customization

- Adjust training parameters such as `epochs`, `batch_size`, or optimizer.

## Acknowledgements

- MNIST Dataset: [Yann LeCun's website](http://yann.lecun.com/exdb/mnist/)
- TensorFlow and Keras: [TensorFlow Official Website](https://www.tensorflow.org/)

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Enjoy using this digit recognition model! Contributions and suggestions are welcome!
