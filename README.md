# e-commerce_clothing_keras
Classify clothes using images with Keras

Study on neural networks to produce an algorithm that can classify images for an e-commerce clothes retail store.

Tasks:
1. Define a CNN classifier as a Sequential model with the following layers:
  Convolution layer with 32 filters, kernel size 3 and stride 1, followed by a rectilinear unit (relu) activation.
  Convolution layer with 16 filters, kernel size 3 and stride 1, followed by a rectilinear unit (relu) activation.
  Flatten layer.
  Dense layer with the appropriate number of units and activation function.
2. Train your CNN on the given train_images using a suitable optimizer.
3. Only run your training loop for a single epoch to keep the run time down.
4. Use accuracy as a metric, and an appropriate loss function.
5. Evaluate your CNN on the given test_images:
  Calculate the accuracy of your trained classifier on the test_images, storing your answer in the variable test_accuracy.
