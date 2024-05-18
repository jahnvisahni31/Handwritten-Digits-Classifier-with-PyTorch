# Handwritten Digits Classifier with PyTorch

This project implements a handwritten digits classifier using PyTorch. The classifier is trained on the popular MNIST dataset, which consists of 28x28 grayscale images of digits (0-9). The goal is to accurately classify these images into their respective digit classes.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Project Structure](#project-structure)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

To get started with this project, you need to install the required dependencies. The dependencies are listed in the `requirements.txt` file. 

1. Clone the repository:
    ```sh
    git clone https://github.com/jahnvisahni31/Handwritten-Digits-Classifier-with-PyTorch.git
    cd Handwritten-Digits-Classifier-with-PyTorch
    ```

2. Create a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

The main code for training and evaluating the model is contained in a Jupyter Notebook file (`.ipynb`). To run the notebook:

1. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

2. Open the `Handwritten-Digits-Classifier.ipynb` file in the Jupyter interface.

3. Run the cells in the notebook sequentially to train the model and evaluate its performance. The notebook includes code for loading the dataset, defining the model, training, and testing.

## Project Structure

The repository contains the following files:

- `requirements.txt`: Lists the Python packages required to run the project.
- `Handwritten-Digits-Classifier.ipynb`: Jupyter Notebook containing the code for the handwritten digits classifier.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

To contribute:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes.
4. Commit your changes:
    ```sh
    git commit -m "Description of changes"
    ```
5. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
6. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
