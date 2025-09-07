Overview

Plant diseases can significantly affect crop yield and food security worldwide. The Plant Disease Predictor is an AI-powered tool designed to help farmers, gardeners, and agricultural experts quickly identify diseases in plants from images of leaves. By leveraging deep learning techniques, this project aims to provide fast, accurate, and easy-to-use disease diagnosis to prevent crop loss and promote healthier farming.


Features

📸 Upload or capture images of plant leaves.

🧠 Uses convolutional neural networks (CNN) for disease classification.

🌱 Supports detection of multiple plant diseases across various crops.

🏆 High accuracy with a user-friendly interface.

📊 Provides detailed disease information and possible remedies.

⚡ Fast inference time suitable for mobile and web deployment.


🛠️ Technologies Used
Python 3.9+

TensorFlow / Keras

OpenCV

NumPy & Pandas

Flask / Streamlit (for app deployment)

Matplotlib / Seaborn (for data visualization)

How to Train Your Own Model

Prepare a labeled dataset of plant leaf images.

Preprocess images using scripts in src/data_preprocessing.py.

Train your model using src/train_model.py with your dataset.

Save the trained model checkpoint in models/.

Update app.py to load your custom model.

