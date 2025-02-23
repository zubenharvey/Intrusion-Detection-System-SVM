# Analysing Network Traffic using Support Vector Machine

Overview:
This project demonstrates how an Intrusion Detection System (IDS) can be implemented using Support Vector Classification (SVC) and Support Vector Regression (SVR). The goal is to analyze network traffic data, preprocess it, and train machine learning models to detect potential cybersecurity threats in real time.

Project Description:
Intrusion detection is a critical aspect of cybersecurity, helping to identify malicious activities in network traffic. This project involves

1. Data Collection: NSL-KDD Dataset is a benchmark dataset for intrusion detection, containing labeled normal and attack traffic. Wireshark Captured Traffic is used as real-time network traffic is also captured using Wireshark, which includes packet details such as source/destination IP, protocol, and payload information.

2. Data Preprocessing: Handling missing values, feature scaling, and encoding categorical data. Extracting meaningful features from Wireshark packet captures (PCAP files).

3. Model Implementation: SVC Model which is a classification approach to distinguish between normal and attack traffic and a SVR Model which is a regression-based approach to predict network behavior deviations.

4. Evaluation: Assessing model performance using metrics like Accuracy and Mean Squared Error (MSE).

Technologies Used:
1. Programming Language- Python
2. Libraries- numpy, pandas, matplotlib, scikit-learn, pyshark

Dataset:
This project utilizes the NSL-KDD dataset, containing labeled network traffic features for intrusion detection, and Wireshark-captured network traffic (PCAP files), which are processed using PyShark to extract relevant features for real-time analysis in both SVC models.

Usage:
1. Download the NSL KDD Dataset if not already included.
2. Update the dataset path in the code if necessary.
3. Download Wireshark to start capturing network packets.
4. Run the corresponding SVC or SVR notebook to test the model.
5. Analyze output metrics and graphs to evaluate performance.
