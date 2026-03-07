# Neural Network for Lander Game 🚀

## Project Overview
Developed a **Feed-Forward Neural Network with Backpropagation** to land a ship in a randomly generated environment safely. The project demonstrates the practical application of machine learning and deep neural network concepts.

## Objective
- Safely land the ship without touching unsafe terrain.
- Train a neural network to replicate successful landings using self-collected gameplay data.

## Approach
- **Data Collection:** Generated training data by playing the game and recording X/Y positions and actions.
- **Model:** Feed-Forward Neural Network with Backpropagation.
- **Inputs:** X and Y positions relative to the landing target.
- **Outputs:** Lander thruster and turning commands.
- **Training:** Offline training (~100 epochs) using collected data.
- **Evaluation:** Tested network performance using Root Mean Squared Error (RMSE).

## Tools & Technologies
- **Programming Language:** Python
- **Libraries:** NumPy, TensorFlow/Keras (optional), Matplotlib for visualization
- **Platform:** Jupyter Notebook / Google Colab
### To run this code:
1. Place your CSV dataset in the `data/` folder.
2. Make sure the file name matches `my_dataset.csv`.

## Results
- Demonstrated understanding of neural network design, backpropagation


