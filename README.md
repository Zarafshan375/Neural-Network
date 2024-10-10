This project uses a CNN to predict age from facial images in the FG-NET dataset, loaded via DeepLake.
Images are preprocessed by resizing to 128x128 pixels and converting grayscale images to RGB.
The dataset is split into training (80%) and testing (20%) sets, and the CNN model is compiled with the Adam optimizer and Mean Squared Error (MSE) loss.
The model is trained for 10 epochs, with Mean Absolute Error (MAE) as the primary evaluation metric.
After training, the script visualizes the training/validation loss and MAE to evaluate model performance.
