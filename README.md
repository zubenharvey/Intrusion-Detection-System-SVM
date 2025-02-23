# Analysing Network Traffic using Support Vector Machine

Overview:
This project demonstrates how an Intrusion Detection System (IDS) can be implemented using Support Vector Classification (SVC) and Support Vector Regression (SVR). The goal is to analyze network traffic data, preprocess it, and train machine learning models to detect potential cybersecurity threats in real time.

Project Description:
Intrusion detection is a critical aspect of cybersecurity, helping to identify malicious activities in network traffic. This project involves

1. Data Collection:
NSL-KDD Dataset: A benchmark dataset for intrusion detection, containing labeled normal and attack traffic.
Wireshark Captured Traffic: Real-time network traffic captured using Wireshark, which includes packet details such as source/destination IP, protocol, and payload information.

3. Data Preprocessing:
2.1 Handling missing values, feature scaling, and encoding categorical data.
2.2 Extracting meaningful features from Wireshark packet captures (PCAP files).

4. Model Implementation:
3.1 SVC Model: A classification approach to distinguish between normal and attack traffic.
3.2 SVR Model: A regression-based approach to predict network behavior deviations.

5. Evaluation: Assessing model performance using metrics like Accuracy and Mean Squared Error (MSE).

Technologies Used:
1. Programming Language- Python
2. Libraries- numpy, pandas, matplotlib, scikit-learn, pyshark

Dataset:
1. NSL-KDD Dataset: Contains network traffic features and attack labels.
2. Wireshark Captured Dataset: Live network traffic captured using Wireshark, which can be converted into CSV format for feature extraction and analysis.

Usage:
1. Download the NSL KDD Dataset if not already included.
2. Update the dataset path in the code if necessary.
3. Download Wireshark to start capturing network packets, save the captured traffic as a PCAP file and convert PCAP files to structured CSV format using PyShark.
4. Run the corresponding SVC or SVR notebook to test the model.
5. Analyze output metrics and graphs to evaluate performance.
