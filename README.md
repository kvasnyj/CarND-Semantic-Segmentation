# Semantic Segmentation
### Hyperparameters
- epochs: 20 (10 is no enought)
- batch_size: 16 (for bigger value I got out of memory expception)
- keep_prob: 0.5
- learning_rate: 0.0001 (0.001 lead to 0.07 loss)

### Result
Loss: 0.014503017999231815 


### Project structure
- load_vgg - Load Pretrained VGG Model into TensorFlow
- layers - Create the layers for a fully convolutional network.
- optimize - Build the TensorFLow loss and optimizer operations.
- train_nn - Train neural network and print out the loss during training.



