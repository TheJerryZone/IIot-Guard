# IIot-Guard-Advanced-cyber-Threat-Detection-system
IIoT Guard is a Flask platform using machine learning (Random Forest, SVM) to detect cyber threats like DDoS and Port Scanning in industrial networks. It offers secure file uploads, model creation, and achieves 100% accuracy in threat detection, providing security teams with an intuitive tool to protect critical infrastructure.

The project supports real-time network packet capture using Wireshark/tshark and saves the captured packets into a CSV file.
Steps to capture in real-time:

1.Run Wireshark or tshark to capture live network traffic.
2.Export the captured packets to wiresharkcapture.csv in the projectt/uploads/ folder (or your designated folder).
3.The application reads this CSV file for real-time threat detection using the ML model.
4.As new packets are captured and saved, the system can continuously process the updated CSV for predictions.
