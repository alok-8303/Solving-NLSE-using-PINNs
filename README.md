# Solving Nonlinear Schrödinger Equation Using PINNs
This project explores the application of Physics-Informed Neural Networks (PINNs) to solve the Nonlinear Schrödinger Equation (NLSE). The NLSE models complex physical phenomena, including solitons, wave packet evolution, and nonlinear optics. This repository demonstrates an innovative machine learning approach to solving partial differential equations by embedding physical laws directly into the loss function.

## Features
### PINN Design:  
A feedforward neural network with 10 hidden layers and 64  neurons per layer.  
Gaussian Activation Function: Optimized for modeling localized wave behaviors.  


### Training Strategy: 
Adam optimizer with a learning rate of 0.001 over 10,000 epochs.

### Evaluation: 
Comparison with analytical solutions to validate model accuracy.

## Key Results
Accurate predictions for the real part of the wave function.  

Slight deviations in the imaginary part, with performance improvements achieved
through hyperparameter tuning.  


Demonstrates the advantages of physics-informed approaches compared to traditional numerical methods.  


## Tools and Libraries
PyTorch: Neural network implementation and training.  

NumPy: Numerical computations.  

Matplotlib: Visualization of results.  

Automatic Differentiation: Gradients computation for the loss function.  


## Challenges and Future Work
Balancing residual and boundary condition loss terms.  

Slight inaccuracies in predicting the imaginary part of the solution.  

Future improvements include adaptive activation functions, dynamic loss weighting, and extension to higher-dimensional problems.  


## References
PINNs by Maziar Raissi  
 
Nonlinear Schrödinger Equation (Wikipedia)