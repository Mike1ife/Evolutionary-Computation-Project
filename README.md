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
![framework](https://github.com/MikeTai1218/Evolutionary-Computation-Project/assets/173041893/6b50fdf1-ad57-49b1-936a-dadc1bbfe2a8)


## Results
### Los Angeles Lakers
![LAL](https://github.com/MikeTai1218/Evolutionary-Computation-Project/assets/173041893/08b8d43a-939c-462a-be8a-47fd5d61ab93)

### Los Angeles Clippers
![LAC](https://github.com/MikeTai1218/Evolutionary-Computation-Project/assets/173041893/2d123b2b-1baf-4c58-b7bc-d39fdd5b8c86)


## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/Mike1ife/Evolutionary-Computation-Project/blob/main/LICENSE) file for more details.
