# LSTM Autoencoder & 2D-LSTM-Autoencoder

Welcome to the **LSTM Autoencoder** and **2D-LSTM-Autoencoder** projects! This repository offers comprehensive examples and implementations of LSTM Autoencoders for both 1D and 2D time series data reconstruction and anomaly detection.

# What is an Autoencoder?

An Autoencoder is a type of neural network that learns efficient representations of data. It works by compressing input data into a latent space representation and then reconstructing the original input from this compressed form. This process is valuable for various tasks, including noise removal, feature extraction, and data reconstruction.

# Applications

# 1. Series Data Reconstruction with LSTM Autoencoders

Autoencoders are designed to compress input data into a latent space representation and then reconstruct it from this compressed form. This technique is useful for removing noise and capturing essential features from the data. For more insights into LSTM Autoencoders and their practical applications, refer to this [blog post](https://adnankarol.medium.com/lstm-autoencoder-9094615a019d).

# 2. Anomaly Detection

LSTM Autoencoders are particularly effective for detecting anomalies in time series data. By training an autoencoder on normal (non-anomalous) data, the model learns to accurately reconstruct these sequences. When the model encounters data with anomalies, the reconstruction error will be significantly higher, making it easier to identify anomalies.

Learn more about anomaly detection using LSTM Autoencoders in my [Medium article on the subject](https://medium.com/analytics-vidhya/lstm-autoencoder-for-anamoly-detection-a0d77bb1540e).

# 3. 2D-LSTM-Autoencoder

Building on the 1D LSTM Autoencoders, this repository also includes an implementation of the 2D LSTM Autoencoder. This extension is designed to handle 2D time series data, offering enhanced capabilities for data reconstruction and anomaly detection.

**Introduction to 2D LSTM Autoencoder:** [Medium article](https://adnanmushtaq5.medium.com/introduction-to-2-dimensional-lstm-autoencoder-47c238fd827f)

This addition focuses on reconstructing and analyzing 2D time series data, applying the principles of LSTM Autoencoders to more complex datasets.

## How It Works

1. **Train the Autoencoder**: The model learns to reconstruct normal sequences from training data.
2. **Evaluate Reconstruction Error**: Calculate the Mean Squared Error (MSE) between the reconstructed output and the original input.
3. **Detect Anomalies**: Assess the reconstruction error for sequences with anomalies. High error values indicate the presence of anomalies.

By leveraging Autoencoders and analyzing reconstruction errors, this project demonstrates effective methods for identifying anomalies in both 1D and 2D time series data.

Explore the code, documentation, and articles provided to gain a deeper understanding of LSTM Autoencoders and their diverse applications.

# Additional Information

- **Python Version**: 3.7.7
- **Pip Version**: 19.2.3

### Contact

For queries or issues, reach out via LinkedIn: [Adnan Karol](https://www.linkedin.com/in/adnan-karol-aa1666179/)