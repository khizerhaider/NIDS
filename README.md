
🚀 Network Intrusion Detection System (NIDS) using LSTM

A deep learning-based Network Intrusion Detection System (NIDS) that detects malicious activities in network traffic using Long Short-Term Memory (LSTM) networks. The model is trained on the UNSW-NB15 dataset to classify network behavior as normal or attack traffic.
📌 Features

✅ LSTM-based deep learning model for sequence-based anomaly detection.
✅ Preprocessed UNSW-NB15 dataset for improved model performance.
✅ Google Colab compatibility for easy training and testing.
✅ Model saved in .h5 format for future predictions.
✅ Predictions exported to CSV for further analysis.
📂 Dataset

The UNSW-NB15 dataset is a benchmark dataset for network intrusion detection, containing:

    49 features representing network behavior.
    9 attack categories, including DoS, Reconnaissance, and Exploits.

📥 Download Dataset: UNSW-NB15
🚀 Installation & Usage
🔹 Clone the Repository

git clone https://github.com/khizerhaider/NIDS/
cd NIDS-LSTM

🔹 Install Dependencies

pip install -r requirements.txt

🔹 Run the Notebook in Google Colab

Upload the Jupyter Notebook (NIDS_LSTM.ipynb) to Google Colab and execute the cells to:
✅ Load & preprocess the dataset
✅ Train the LSTM model
✅ Evaluate and test predictions
✅ Save the trained model
📊 Model Training & Evaluation

The LSTM model is trained with:

    Input Shape: (1, num_features)
    Loss Function: Binary Cross-Entropy
    Optimizer: Adam
    Metrics: Accuracy

📁 Saved Model: lstm_nids_unsw_nb15.h5
📄 Predictions File: lstm_predictions.csv
📤 Upload Model & Notebook to GitHub

To upload the Colab Notebook and Saved Model (.h5 file) to GitHub, follow these steps:
1️⃣ Mount Google Drive in Colab

from google.colab import drive
drive.mount('/content/drive')

2️⃣ Move the Model & Notebook to GitHub Folder

!mv /content/lstm_nids_unsw_nb15.h5 /content/NIDS-LSTM/
!mv /content/NIDS_LSTM.ipynb /content/NIDS-LSTM/

3️⃣ Push to GitHub from Colab

!git init
!git remote add origin https://github.com/YOUR_USERNAME/NIDS-LSTM.git
!git add .
!git commit -m "Added NIDS LSTM model and notebook"
!git push origin main

📌 Future Improvements

🔹 Fine-tune hyperparameters for better accuracy.
🔹 Explore Transformer-based architectures for NIDS.
🔹 Deploy the model as a web API for real-time detection.
🤝 Contributing

Pull requests are welcome! Feel free to fork the repo and submit improvements.
🛡️ License

This project is licensed under the MIT License.
✨ Connect with Me

🔗 GitHub: [YOUR_GITHUB_PROFILE](https://github.com/khizerhaider)
🔗 LinkedIn: [YOUR_LINKEDIN](https://www.linkedin.com/in/syed-muhammad-khizer-haider-152792291/)
