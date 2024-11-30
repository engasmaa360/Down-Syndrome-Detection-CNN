# Down-Syndrome-Detection-CNN

📋 Overview
This project aims to leverage deep learning techniques to detect Down Syndrome using facial features. By building a Convolutional Neural Network (CNN), the model classifies images as either "Down Syndrome" or "Healthy," aiding in early diagnosis.

🧬 Problem Statement
Down Syndrome is a genetic disorder caused by an extra 21st chromosome.

Prevalence: Affects 1 in 800 births globally.
Challenges: Distinct physical traits and variability in facial features make detection challenging.
This project tackles these challenges by analyzing key facial features through image classification.
📊 Dataset
Size: 3,000 images.
1,500 images of children with Down Syndrome.
1,500 images of healthy children.
Features:
Distance between the eyes.
Distance between the eyes and the mouth.
Preprocessing:
Resized and normalized images.
Dataset split into training (80%) and testing (20%).
🛠️ Methodology
Data Preprocessing:

Images resized to a standard dimension and normalized.
Key features extracted for better model accuracy.
Model Architecture:

Input Layer: Preprocessed images.
Convolutional Layers: Extract facial patterns and features.
Pooling Layers: Reduce dimensionality.
Dense Layers: Fully connected for classification.
Activation Functions: ReLU (hidden layers), Softmax (output layer).
Training:

Optimizer: Adam optimizer.
Loss Function: Binary cross-entropy.
Evaluation Metrics: Accuracy, Precision, Recall, AUC.
🔑 Results
Best AUC Score: 0.878.
The model effectively distinguishes between "Down Syndrome" and "Healthy" classes despite subtle feature differences.
🚀 Challenges
Inconsistent Visual Features: Subtle differences in facial traits.
Feature Variability: Variations in lighting, angles, and image quality.
Class Balance: Distinctiveness of Down Syndrome features posed classification challenges.
📈 Future Improvements
Expand the dataset with more diverse images.
Incorporate advanced feature extraction techniques.
Explore transfer learning to improve accuracy.
💻 Tools & Technologies
Programming Language: Python
Framework: TensorFlow
Libraries: NumPy, Matplotlib, Pandas
📂 Project Structure
DEBI_final_pro.ipynb: The Jupyter Notebook containing the implementation.
data/: Directory for the dataset (not included here for privacy).
results/: Directory for storing model outputs and logs.
