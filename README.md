# Advanced Learning Algorithms - Neurons and Layers

This project demonstrates the implementation of basic neural network concepts using TensorFlow and Keras. It includes examples of linear and logistic regression models, visualization of data, and manipulation of model weights.

## Project Structure

- **`main.py`**: The main Python script that contains the implementation of linear and logistic regression models using TensorFlow.
- **Dependencies**: The project uses external libraries such as TensorFlow, NumPy, and Matplotlib for computations and visualizations.

## Features

1. **Linear Regression**:
   - Creates a linear model using Keras.
   - Visualizes the relationship between input features and predictions.
   - Demonstrates how to manually set weights and biases for the model.

2. **Logistic Regression**:
   - Implements a logistic regression model using Keras.
   - Visualizes the sigmoid activation function and its predictions.
   - Demonstrates how to manually set weights and biases for the logistic layer.

3. **Visualization**:
   - Uses Matplotlib to plot data points and model predictions.
   - Includes custom plotting functions for linear and logistic regression.

## Requirements

- Python 3.7 or higher
- TensorFlow 2.x
- NumPy
- Matplotlib

## Installation

1. Clone the repository or download the project files.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   If a `requirements.txt` file is not available, manually install the dependencies:
   ```bash
   pip install tensorflow numpy matplotlib
   ```

## Usage

1. Run the `main.py` script:
   ```bash
   python main.py
   ```
2. The script will:
   - Plot the data points for linear and logistic regression.
   - Display the model summary and predictions.
   - Show visualizations of the model's performance.

## File Descriptions

- **`main.py`**: Contains the implementation of the models and visualizations.
- **`deeplearning.mplstyle`**: A custom Matplotlib style file for consistent plotting aesthetics.
- **`lab_utils_common.py`** and **`lab_neurons_utils.py`**: Utility files for plotting and other helper functions.

## Example Output

- Scatter plots of data points for linear and logistic regression.
- Model predictions visualized alongside the data.
- Console output of model weights, biases, and predictions.

## Notes

- Ensure that TensorFlow is installed correctly. If you encounter issues, refer to the [TensorFlow installation guide](https://www.tensorflow.org/install).
- The project is designed for educational purposes to demonstrate basic neural network concepts.

## License

This project is for educational purposes and does not include a specific license.
