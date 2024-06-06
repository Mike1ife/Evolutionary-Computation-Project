# Evolutionary Computation Project

Novel playing time allocation for professional sport teams using evolutionary algorithm and deep learning techniques

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Methods](#methods)
- [Results](#results)
- [License](#license)

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
    ```sh
    https://github.com/Mike1ife/Evolutionary-Computation-Project.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Evolutionary-Computation-Project
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To run the project, execute the following command:
```sh
python main.py
```
Ensure you have the necessary datasets in the dataset folder.

## Project Structure
- main.py: The main script for running the genetic algorithm and predicting win rates.
- model.py: Contains the neural network model definition.
- load.py: Handles data loading and preprocessing.
- train.py: Script for training the model using cross-validation.

## Methods
### Data Loading and Preprocessing
The load.py script reads player statistics from CSV files, normalizes them, and prepares training and testing datasets.

### Evolutionary Algorithm
- Tournament Selection
- Uniform Crossove
- Gaussian Mutation
- Self-defined Fitness Function

### Model
The neural network model defined in model.py consists of four linear layers with ReLU activation and batch normalization.

### Training
The train.py script trains the model and uses Leave-One-Out Cross-Validation (LOOCV) to evaluate its performance.

## Results

## License
This project is licensed under the MIT License. See the License file for more details.
