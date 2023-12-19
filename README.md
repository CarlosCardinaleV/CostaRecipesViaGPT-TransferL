# Costa Rican Dish Recipe Generation using GPT-2 and GPT-Neo

This project demonstrates the application of transfer learning using GPT-2 and GPT-Neo models for generating Costa Rican dish recipes. The project compares the performance of these models on two different datasets.

## Project Description

The main goal of this project is to fine-tune the GPT-2 and GPT-Neo-125M transformer models for recipe generation, specifically focusing on Costa Rican dishes. The project involves training these models on two separate datasets and analyzing their performance.

## Setup and Installation

1. **Dependencies Installation:**
   - Ensure Python 3.x is installed.
   - Install required packages: `torch`, `transformers`, `matplotlib`.
   - Install additional dependencies as per your system (CUDA for GPU acceleration, etc.).

2. **Clone the Repository:**
   - Clone this repository to your local machine.

3. **Dataset Preparation:**
   - Place the recipe datasets in the `dataset-transformers` folder.

## Usage

1. **Dataset Splitting:**
   - Run the provided script to split each dataset into training and validation sets.

2. **Model Fine-Tuning:**
   - Use the provided scripts to fine-tune GPT-2 and GPT-Neo models on each dataset.

3. **Training and Validation:**
   - Monitor the training and validation losses using the matplotlib plots.

4. **Evaluation and Comparison:**
   - Compare the performance of each model on both datasets.

## File Structure

- `dataset-transformers/`: Contains the recipe datasets.
- `train_dataset_v1.txt`: Training data for the first dataset.
- `validation_dataset_v1.txt`: Validation data for the first dataset.
- Additional scripts for model training and evaluation.

## Performance Metrics

The project evaluates models based on training and validation losses. These metrics help in understanding the model's learning efficiency and generalization capability on unseen data.

## Contributing

Contributions to this project are welcome. Please read the contributing guidelines before making a pull request.

## License
[![Licencia: MIT](https://img.shields.io/badge/Licencia-MIT-amarillo.svg)](./LICENSE)