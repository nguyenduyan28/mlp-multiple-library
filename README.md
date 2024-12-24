## Flow 

### 1.  Preprocessing (temporarily done)
### 2. Model design
- Number of layers 
- Number of neurons per layer
- Activation functions
- Dropout or batch normalization
- Using: 
  - sklearn, pytorch --> Hanh
  - tensorflow, optional --> An
  - report --> An

### 2.1 Selecting loss function and optimizer
- Loss : cross-entropy loss and binary cross-entropy loss
- Optimizer: SGD, Adam


### 2.2 Model training
- Epochs: Specify num of epochs
- Batch size : Free Choosing
- Traning process: Perform forward propagation --> Compute loss --> update w using backpropagation.
- Early stopping: Monitor the validation set performance during training process and stop if it doesn’t improve after a set number of epochs.
- **NOTE** : Remember to record the training time and GPU consumption of libraries and frameworks during train process.  


### Model Evaluation
- Evaluation metrics: Accuracy , precision, recall, F1-score, ...
- Confusion matrix : used for analyzing how the model perform

