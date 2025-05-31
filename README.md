🚀 Insurance Premium Predictor (FastAPI & Streamlit)
A full-stack machine learning application that predicts the insurance premium category for users based on their age, BMI, income, occupation, city tier, and smoking habits.

🧠 Project Overview
This project integrates a trained ML model into a FastAPI backend with a Streamlit frontend. It takes user inputs, computes dynamic risk factors (like BMI and lifestyle risk), and predicts the insurance premium category in real time.

🔧 Tech Stack
Backend: FastAPI, Pydantic, Scikit-learn

Frontend: Streamlit

Language: Python

Libraries: Pandas, Requests, joblib

📦 Features
Real-time insurance premium prediction

BMI, lifestyle risk, and age group computed dynamically

Tier-based city classification

Streamlit-based user-friendly UI

Clean and modular codebase

📌 How to Run
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/insurance-premium-predictor.git
cd insurance-premium-predictor
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Start FastAPI backend
bash
Copy
Edit
uvicorn main:app --reload
4. Run Streamlit frontend
bash
Copy
Edit
streamlit run app.py
Insurance_Premium_Prediction/
├── app.py                   # FastAPI backend with prediction API
├── frontend.py              # Streamlit frontend UI
├── fastapi_ml_model.ipynb   # Jupyter notebook for model training
├── model.pkl                # Saved machine learning model (generated after training)
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
📷 Demo
![Screenshot (37)](https://github.com/user-attachments/assets/9fc4fcb9-842e-4abb-9f03-a4f300b64566)
![Screenshot (36)](https://github.com/user-attachments/assets/8dfff7bc-df23-418c-bce6-b06a58ae4efa)
![Screenshot (34)](https://github.com/user-attachments/assets/4734e1d7-2ab2-4921-aa4f-84036bf8b27f)
![Screenshot (33)](https://github.com/user-attachments/assets/9477be0d-eea5-4b37-8b78-2969c270b606)
![Screenshot (32)](https://github.com/user-attachments/assets/a341a5b3-d84a-432b-96f2-2abc3cb35bbf)
![Screenshot (31)](https://github.com/user-attachments/assets/1f22d0f8-ca01-4885-ab78-244c19045ba6)
![Screenshot (30)](https://github.com/user-attachments/assets/e600d096-4b2f-48a9-895f-b5f18ae4f2f6)
