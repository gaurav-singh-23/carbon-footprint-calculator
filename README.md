# 🌱 Carbon Footprint Calculator

A **machine learning–based web application** that estimates an individual’s carbon footprint based on lifestyle and consumption inputs.  
The application is built using **Python and Streamlit** and is **deployed on AWS EC2** for public access.

---

## 🚀 Live Demo
http://51.21.110.137:8501/

---

## 📌 Features
- 🌍 Estimates carbon footprint based on user inputs
- 📊 Uses a trained machine learning model for prediction
- 🖥️ Interactive and user-friendly Streamlit interface
- ☁️ Deployed on AWS EC2 for remote accessibility
- 🔁 Runs as a background service for continuous availability

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend & Machine Learning
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

### Cloud & Deployment
- AWS EC2 (Ubuntu)
- Elastic IP
- Linux (SSH)
- systemd (24/7 execution)

---

## 📂 Project Structure
Carbon_Footprint_Calculator/
│
├── app.py               # Main Streamlit app
├── functions.py         # Helper functions
├── train_model.py       # Model training script
├── models/              # Saved ML models
├── data/                # Dataset files
├── style/               # UI styling files
├── notebooks/           # Jupyter notebooks (optional)
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation



---

## ⚙️ Installation & Local Setup

1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Carbon_Footprint_Calculator.git
cd Carbon_Footprint_Calculator

2️⃣ Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the application
streamlit run app.py

---

## ☁️ AWS Deployment Overview

The application was deployed on an AWS EC2 Ubuntu instance with the following steps:

Created an EC2 instance and configured security groups

Enabled SSH access for remote server management

Installed Python and required dependencies

Created a Python virtual environment

Deployed the Streamlit application

Configured the app to run as a systemd service for:

24/7 availability

Automatic restart on reboot

Attached an Elastic IP to ensure a stable public endpoint


👤 Author

Gaurav Singh

GitHub: https://github.com/gauravsinghgkp

LinkedIn: https://www.linkedin.com/in/gauravsinghgkp


