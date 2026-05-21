# Power Plant Energy Prediction using ANN

In this project, I implemented concepts of Artificial Neural Networks (ANN) by performing regression on the Power Plant Energy Prediction dataset. The objective of the project was to predict power plant energy output based on different environmental parameters.

I approached this by preprocessing and analyzing the dataset, preparing the data for training, building an ANN architecture from scratch using PyTorch, training and validating the model, and finally evaluating the prediction performance of the network.

# Learnings
- Learnt about regression problems using neural networks
- Data preprocessing and feature scaling techniques
- ANN architecture and forward propagation concepts
- Training and validation loss analysis
- Optimization techniques and loss functions
- Model evaluation and prediction analysis using regression metrics
  
# Debugging
- Fixed logical and implementation mistakes during model building and training
- Optimized the training pipeline for smoother convergence
- Verified proper preprocessing and tensor conversion of dataset
- Checked training and validation losses to ensure stable learning
- Tuned model parameters to improve prediction performance

These improvements helped the ANN model learn dataset patterns effectively and achieve stable prediction performance.

# Results

The ANN model was able to learn relationships between input environmental features and power output effectively. The training and validation loss curves showed a continuous decrease over epochs, indicating stable learning and successful convergence of the model.

The close alignment between training loss and validation loss suggests that the model generalized well on unseen data and avoided major overfitting issues.

## Training and Validation Loss Graph

<p align="center">
  <img src="results/losscurve.png" width="700"/>
</p>

<p align="center">
  <em>Training vs Validation Loss across epochs for the ANN regression model.</em>
</p>
