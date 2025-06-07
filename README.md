# Anamoly-Detection-DeepLearning
Anomaly-Activity-Detection-on-Real-Time-Surveillance-Videos-with-Deep-Learning

This project aims to detect anomalous activities in real-time surveillance videos using deep learning techniques. By leveraging Convolutional Neural Networks (CNNs), the system can identify unusual events, enhancing security and monitoring systems.

🗂️ Project Structure
The repository contains the following Jupyter Notebooks:

1_Creat_datset_Final.ipynb: Prepares and organizes the dataset for training and testing.

2_Extract_Frames.ipynb: Extracts individual frames from surveillance videos.

3_CNN_TrainModel.ipynb: Trains a CNN model on the extracted frames to learn patterns of normal and anomalous activities.

4_Main_Test.ipynb: Tests the trained model on new video data to detect anomalies.

🛠️ Getting Started
Prerequisites
Python 3.x
Jupyter Notebook
Required Python libraries (e.g., TensorFlow, OpenCV, NumPy)


🚀 Usage
Dataset Preparation: Run 1_Creat_datset_Final.ipynb to organize your dataset into appropriate training and testing directories.

Frame Extraction: Use 2_Extract_Frames.ipynb to extract frames from your video files. This step converts videos into a series of images for model training.

Model Training: Execute 3_CNN_TrainModel.ipynb to train the CNN model on the extracted frames. The model will learn to distinguish between normal and anomalous activities.

Model Testing: Run 4_Main_Test.ipynb to test the trained model on new video data. The model will predict and highlight any detected anomalies.

📊 Results
The trained model can effectively identify anomalies in surveillance videos, aiding in real-time monitoring and security enforcement. Visualizations and performance metrics can be generated during the testing phase to evaluate model accuracy.

🤝 Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.
