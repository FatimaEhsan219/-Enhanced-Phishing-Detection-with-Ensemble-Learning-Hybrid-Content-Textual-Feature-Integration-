# Phishing Email Detection Using Ensemble Learning

This project presents a **phishing email detection methodology** that combines **Ensemble Learning** with **hybrid features** (content-based and textual) to improve detection accuracy. It utilizes **Stacking** and **Soft Voting** ensemble methods to process features separately in parallel, reducing complexity and enhancing performance. The proposed model achieves an **F1-score of 0.9942** on a large, imbalanced dataset of phishing and benign emails.

## 🔥 Key Features
- **Hybrid Feature Extraction**: Combines content-based and textual features for better phishing detection.
- **Ensemble Learning**: Uses Stacking and Soft Voting to enhance model accuracy.
- **High Performance**: Achieves an **F1-score of 0.9942**, outperforming traditional models.
- **Google Colab Support**: Easy-to-run Python notebooks for experimentation.
- **Rich Dataset**: Trained on a dataset with **32,051 benign** and **3,460 phishing** emails.

## 📂 Repository Structure
/Phishing-Email-Detection
│── README.md               # Already written
│── requirements.txt        # Dependencies for the project
│── data/
│   ├── phishing_emails.csv # Processed dataset
│   ├── benign_emails.csv   # Processed dataset
│── notebooks/
│   ├── phishing_detection.ipynb  # Google Colab notebook for training & evaluation
│── src/
│   ├── preprocess.py        # Script for data preprocessing
│   ├── feature_extraction.py # Script for feature extraction
│   ├── ensemble_model.py    # Script for training ensemble models
│── results/
│   ├── evaluation_metrics.txt # Contains F1, Accuracy, Precision, Recall, etc.
│   ├── confusion_matrix.png   # Image of confusion matrix
│── LICENSE                  # Open-source license (e.g., MIT)
│── .gitignore               # Ignore unnecessary files


Run the Google Colab notebook
Open the notebook in the notebooks/ folder.
Follow the steps to preprocess data, train the model, and evaluate performance.


🚀 Usage
Run feature extraction to process email content.
Train the model using Stacking and Soft Voting ensemble methods.
Evaluate model performance with precision, recall, F1-score, and accuracy.


📊 Performance
Stacking Ensemble Learning: High precision and recall.
Soft Voting Ensemble Learning: Best overall performance (F1-score 0.9942).
Comparison with Baseline Models: Outperforms traditional ML approaches.



📜 License
This project is licensed under the MIT License.



🤝 Contributing
Feel free to submit issues and pull requests to improve the project.

