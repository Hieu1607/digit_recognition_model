# MNIST Project

This project uses TensorFlow to train a Convolutional Neural Network (CNN) model to predict handwritten digits from the MNIST dataset.

## Project Structure

- **`build_model.ipynb`**: Jupyter Notebook containing the code to load the MNIST dataset, preprocess the data, build and train the CNN model, and evaluate its performance.
- **`mnist_model_2.h5`**: Saved model file after training.
- **`requirements.txt`**: List of Python dependencies required to run the project.
- **`.gitignore`**: Specifies files and directories to be ignored by Git.

## Requirements

Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the `build_model.ipynb` file in Jupyter Notebook.
2. Run the cells step by step to:
   - Load and preprocess the MNIST dataset.
   - Build and train the CNN model.
   - Evaluate the model's performance.
   - Save and visualize the results.

## Output

- The trained model is saved as `mnist_model_2.h5`.
- The notebook includes visualizations of training accuracy, validation accuracy, and loss.

## Dataset

The MNIST dataset is automatically downloaded using TensorFlow's `datasets.mnist.load_data()` function.

## License

This project is for educational purposes.