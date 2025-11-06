# Diploma Final Project
# Maintainer stud. Luca Plian
## AI-Powered Analysis in Smart Home Environment

This project is developed as part of my diploma thesis at the **University Politehnica of Bucharest**, Faculty of Automatic Control and Computers.  
It explores the use of **Artificial Intelligence (AI)** and **IoT sensor data** for understanding and optimising human behaviour in a smart home environment.

## Project Overview
The goal of this project is to develop a modular system capable of:
1. **Recognising human activities (HAR)** plan to use Wi-Fi CSI (Channel State Information) signals through deep learning models (e.g. Bi-LSTM);
2. **Analysing behavioural patterns** to distinguish between *automated*, *optimising*, and *negative* behaviours;
3. **Triggering or recommending smart home actions** (e.g. turn lights on, restrict screen use, optimise sleep routines) based on learned patterns.




The work combines principles from:
- **Ambient Assisted Living (AAL)** – AI & IoT for improving quality of life;
- **Human Activity Recognition (HAR)** – detecting daily activities from sensor data;
- **Smart Home Automation (SHA)** – enabling adaptive and predictive control.



The structure of project is like this:
diploma/
│
├── data/  **datasets dedicated folder**
├── notebooks/   **notebooks folder**
├── src/  **functions dedicated folder**
├── docs/ **folder related to relevant references, and dataset**
├── results/ **folder storing results related to har and actuator**
├── README.md
├── CHANGELOG.md
├── requirements.txt
└── LICENSE



## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
git clone https://github.com/lucaplian/diploma
cd diploma
pip install -r requirements.txt
