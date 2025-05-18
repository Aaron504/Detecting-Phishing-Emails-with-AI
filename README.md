# Detecting Phishing Emails with AI
<p align="center">

![Screenshot 2025-05-17 211739](https://github.com/user-attachments/assets/481bb5a8-1e4a-483c-a4ae-663235dd30b8)


<h1>Phishing Email Detection with AI (Logistic Regression)</h1>

This project demonstrates the use of machine learning to detect phishing emails based on their textual content. Built and executed entirely within a Windows-based Azure Virtual Machine, it uses a Logistic Regression model trained on sample email data labeled as either phishing or legitimate.

The emails were preprocessed using TF-IDF vectorization, and the model was evaluated with accuracy and F1-score. A simple Python script simulates real-time predictions on new email inputs using the trained model.

Key Features:

- Created and labeled a custom dataset of phishing vs. legitimate emails
- Converted email text into numerical features using TF-IDF
- Trained and tested a logistic regression classifier using scikit-learn
- Saved the model for future predictions using pickle
- Built a live testing script to simulate real-time detection of phishing emails



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol
- Python 3
- Command Prompt

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- PHASE 1: Create the Phishing Email Dataset
- PHASE 2: Train the Phishing Email Classifier
- Phase 3: Run the Script in Command Prompt
- PHASE 4: Use the Trained Model to Detect Phishing Emails

<h2>Deployment and Configuration Steps</h2>

PHASE 1: Create the Phishing Email Dataset

This Python script creates a small, structured dataset to simulate phishing and legitimate emails. It uses basic examples of email text and labels them as either phishing (1) or legitimate (0). The script stores the dataset in a CSV file (emails.csv), which will be used to train a machine learning model.

Purpose:
To provide a simple, controlled dataset to train and test a phishing email detection algorithm.

Key Features:

- Manually created email samples mimicking real-world phishing and safe email content

- Binary labels: 1 for phishing, 0 for legitimate

- Output stored in a CSV file for easy use in model training

![Screenshot 2025-05-17 194518](https://github.com/user-attachments/assets/a757e384-f178-46c9-b44e-1d98f06e8898)
![Screenshot 2025-05-17 200448](https://github.com/user-attachments/assets/0131e4aa-a585-4cc9-98c6-7ca1ff5b09c9)

PHASE 2: Train the Phishing Email Classifier

![Screenshot 2025-05-17 201408](https://github.com/user-attachments/assets/600b62ed-d4b0-4f3f-aa2f-9f861834bdba)
![Screenshot 2025-05-17 201429](https://github.com/user-attachments/assets/bfa2fb08-a7d8-4fd0-8090-75cf6233df01)

PHASE 3: Run the Script in Command Prompt

Model Training and Evaluation (Logistic Regression)
In this phase, I trained a machine learning model using the Logistic Regression algorithm to detect phishing emails. The model was trained on a labeled dataset of sample email texts and used TF-IDF vectorization to convert raw email content into numerical features.

![Screenshot 2025-05-17 202135](https://github.com/user-attachments/assets/ed0a6fe1-d190-42f8-af47-14bdc6e933ef)

PHASE 4: Use the Trained Model to Detect Phishing Emails

This step simulates how a security system would flag phishing emails in real-time using my AI model.

![Screenshot 2025-05-17 210151](https://github.com/user-attachments/assets/9f1033ee-25ac-4774-8585-c137ab91f49b)
![Screenshot 2025-05-17 210528](https://github.com/user-attachments/assets/1aaf3bd0-1f16-4487-aa2f-394c9c1b2b95)




