# Chess Engine with CNN Evaluation

## Overview

This project aims to build a fully functional chess engine that recommends the best moves for a given chess position. The engine leverages a Convolutional Neural Network (CNN) to evaluate positions, integrated with a mini-max algorithm to explore possible moves and determine the best one.

## Features

- **Dataset Generation**: Utilizes the `python-chess` library to generate random chess boards. These boards are then processed into 3-D numpy arrays suitable for neural network input.
- **CNN Model**: A convolutional neural network is trained on the generated dataset. Labels for the dataset are obtained by evaluating positions using Stockfish.
- **Move Evaluation**: The trained CNN model evaluates new positions encountered during a game. The mini-max algorithm uses these evaluations to explore legal moves up to a certain depth and decide on the best move.

## Requirements

- Python 3.x
- numpy
- python-chess
- tensorflow
- stockfish (ensure Stockfish engine is installed and accessible)

## Installation

1. Clone the repository

2. Install the required Python packages:

3. Ensure Stockfish is installed and accessible from your system. You can download it from [here](https://stockfishchess.org/download/). Make sure that the path to stockfish
   in the code is replaced with the actual path in the system

