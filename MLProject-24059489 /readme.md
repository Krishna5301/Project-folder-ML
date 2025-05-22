UNSW-NB15 Dataset Project: A Closer Look at Network Intrusion Detection
Project Overview
This project explores the UNSW-NB15 dataset, a valuable resource for analyzing and detecting network intrusions. The dataset simulates real-world scenarios by combining normal and malicious network traffic, making it ideal for evaluating intrusion detection systems (IDS).

Dataset Source
The dataset is publicly available on Kaggle:
[UNSW-NB15 Dataset on Kaggle](https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15?select=UNSW_NB15_training-set.csv)

Dataset Description
Developed by the Australian Centre for Cyber Security (ACCS), the UNSW-NB15 dataset includes a mix of real and synthetic network activity. It captures both everyday traffic and various types of cyberattacks, providing a realistic environment for IDS research.

The dataset is divided into four CSV files:

UNSW-NB15_1.csv
UNSW-NB15_2.csv
UNSW-NB15_3.csv
UNSW-NB15_4.csv
Feature Breakdown
Each file contains 43 features (excluding the ID and label columns), grouped into several categories:

Flow Features
These describe the basic flow of network traffic:

srcip, dstip: Source and destination IP addresses
sport, dsport: Source and destination port numbers
proto: Protocol used (e.g., TCP, UDP)
state: Connection state (e.g., FIN, CON)
dur: Duration of the connection
sbytes, dbytes: Bytes sent from source to destination and vice versa
sttl, dttl: Time-to-live values
sloss, dloss: Packet loss from source and destination
service: Type of service (e.g., HTTP, FTP)
Basic Features
These provide a snapshot of traffic volume:

sload, dload: Bits per second from source and destination
spkts, dpkts: Packet counts in each direction
Content Features
These offer deeper insights into the structure of the traffic:

swin, dwin: TCP window sizes
stcpb, dtcpb: TCP base sequence numbers
smeansz, dmeansz: Average packet sizes
trans_depth: HTTP transaction depth