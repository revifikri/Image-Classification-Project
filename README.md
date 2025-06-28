
## Model Summary

This project implements an image classification model that distinguishes among five flower categories—daisy, dandelion, roses, sunflowers, and tulips—using a custom Convolutional Neural Network trained from scratch. The trained model is exported into multiple formats for deployment on various platforms, including server/cloud, mobile/embedded, and web environments.

- **Input**: Flower image (resized to 224x224 RGB)
- **Output**: Predicted class out of 5 flower categories
- **Model architecture**: Custom CNN with five convolutional blocks (32→64→128→256→512 filters), each followed by batch normalization and pooling, a global average pooling layer, and fully connected layers (512→256 units) with dropout and batch normalization.
- **Performance**: Achieved ~90% accuracy on the test set (adjust according to your results)

## Exported Formats

- **SavedModel**: For TensorFlow serving or  cloud deployment
- **TFLite**: For mobile/edge inference
- **TFJS**: For  running the model in web browsers using TensorFlow.js