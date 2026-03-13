Spam Email Detection Project
📌 Project Description
This project implements a Spam Email Detection System using Natural Language Processing (NLP) and Machine Learning. The goal is to classify emails into two categories:
- Ham (legitimate emails)
- Spam (unwanted or malicious emails)
The workflow includes:
- Data exploration and visualization
- Text preprocessing (cleaning, tokenization, removing special characters)
- Feature extraction using TF-IDF
- Model training with Naive Bayes
- Evaluation using accuracy, confusion matrix, and classification report
- Custom email prediction function

  
📊 Dataset Details
- Source: email.csv (SMS Spam Collection dataset)
- Size: 5,573 entries
- Columns:
- Category: Label (ham or spam)
- Message: The email/SMS text
- Distribution:
- Ham: 4,825 messages
- Spam: 747 messages

  
🎯 Model Accuracy
The Multinomial Naive Bayes classifier achieved:
- Accuracy: 97.57%
- Classification Report:
- Ham → Precision: 0.97, Recall: 1.00, F1-score: 0.99
- Spam → Precision: 1.00, Recall: 0.83, F1-score: 0.91
This demonstrates strong performance in detecting spam while minimizing false positives.


⚙️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn (visualization)
- Scikit-learn (TF-IDF, Naive Bayes, evaluation metrics)
- Regex (text cleaning)

  
🛠 Steps to Download & Run
- Go to your GitHub repository
- Open your repo link in a browser

  (e.g., https://github.com/your-username/spam-email-detection).
- Download the project
- Click the green Code button.
- Choose Download ZIP and extract it to a folder on your computer.
- Alternatively, if you have Git installed, run:

  
git clone https://github.com/your-username/spam-email-detection.git
- Navigate to the project folder

  
cd spam-email-detection
- Install dependencies
- Make sure you have Python installed (≥3.8 recommended).
- Install required libraries:

  
pip install -r requirements.txt


pandas
numpy
matplotlib
seaborn
scikit-learn
- Run the project


python spam_detection.py



- You can modify these lines to test with your own email text.
