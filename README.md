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
# Start predicting the time allocation
python main.py
# Train the model as the core of the fitness function
python train.py
```
Ensure you have the necessary datasets in the dataset folder.</br>
Data Sources: [2020-2022](https://www.kaggle.com/datasets/davidabrahamsmith/nba-players-per-game-and-advanced-stats-19802021) [2022-2023](https://www.kaggle.com/datasets/jamiewelsh2/nba-per-game-player-statistics-2022-2023-season) [Team Winrate (label)](https://www.teamrankings.com/nba/stat/win-pct-all-games)

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
The train.py script uses Leave-One-Out Cross-Validation (LOOCV) to evaluate the model's performance and trains it with the whole dataset.

## Results

## License
This project is licensed under the MIT License. See the License file for more details.
