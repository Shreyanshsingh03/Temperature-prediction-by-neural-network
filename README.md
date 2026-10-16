# Temperature-prediction-by-neural-network
Temperature prediction using PyTorch, heat-transfer physics, and Matplotlib in solid conductor of heat
# AI-Based Temperature Prediction Using PyTorch

## Project Overview
This project uses a feedforward neural network built with PyTorch to predict temperature based on time, initial temperature, ambient temperature, and a thermal response constant. Synthetic data is generated using a simplified lumped thermal model.

## Objectives
- Apply deep learning to a heat-transfer problem.
- Train and evaluate a neural network using PyTorch.
- Compare neural network predictions with a physics-based equation.
- Evaluate prediction accuracy and robustness to input noise.
- Visualize model performance using Matplotlib.

## Methodology
1. Generate 500 synthetic temperature observations using a thermal model.
2. Split the dataset into training, validation, and testing sets.
3. Normalize input features using training-set statistics.
4. Train a feedforward neural network using PyTorch.
5. Evaluate performance using MAE, RMSE, and R².
6. Compare predictions with the physics-based model and test sensitivity to input noise.

## Model Performance

| Metric | Result |
|---|---:|
| Test MAE | 1.0414 °C |
| Test RMSE | 1.5126 °C |
| Test R² | 0.9890 |
| MAE with noisy inputs | 1.1139 °C |
| Physics-model MAE | Approximately 0.00000076 °C |

## Technologies Used
- Python
- PyTorch
- NumPy
- Matplotlib
- Heat Transfer Fundamentals

## Limitations
The dataset is synthetic and generated from the same physics equation used for comparison. Therefore, the results demonstrate a machine-learning workflow rather than validated performance on real industrial equipment.

## Future Improvements
- Validate predictions using real temperature sensor data.
- Explore more complex heat-transfer conditions.
- Compare different neural network architectures.
- Investigate physics-informed neural networks.

## Author
Shreyansh Singh  

