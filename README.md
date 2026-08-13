 Nexariza AI — AI/ML Internship
6 Weeks. 6 Real AI/ML Systems. Built, Shipped & Documented in Public.

Intern: Fiza Aslam
Duration: 6 Weeks
Status: 🟢 In Progress

📌 About This Repository
This repository documents my AI/ML Internship at Nexariza AI.
Each week I build a real, deployable AI/ML system — from EDA to production-ready models.

What's Inside?
✅ Complete code for each week's project

✅ Detailed READMEs with setup instructions

✅ Demo screenshots & visualizations

✅ LinkedIn posts & documentation

✅ Streamlit apps for each project

📊 Weekly Progress
#	Project	What It Does	Status
1	Wine Quality Prediction	Predict wine quality using chemical properties (94.2% accuracy)	✅ Complete
2	Client Churn Predictor	Predict which clients are at risk of leaving	🔜 Coming
3	Content Quality Classifier (NLP)	Classify LinkedIn posts as High/Medium/Low quality	🔜 Coming
4	Logo & Brand Detector (CV)	Detect Nexariza logo in images using YOLOv8	🔜 Coming
5	MLOps Deployment	Deploy churn model as API with Docker + FastAPI	🔜 Coming
6	🏆 AI Business Dashboard	Complete analytics dashboard with forecasting	🔜 Coming
🛠️ Tech Stack
Category	Technologies
Languages	Python 3.11
Data	Pandas, NumPy
Visualization	Matplotlib, Seaborn, Plotly
Machine Learning	Scikit-learn, XGBoost
Deep Learning	PyTorch, TensorFlow
NLP	HuggingFace Transformers, BERT
Computer Vision	YOLOv8, OpenCV, ResNet
MLOps	FastAPI, Docker, MLflow
Dashboard	Streamlit
Version Control	Git, GitHub
📁 Repository Structure
text
Nexariza_AI_ML_Internship/
│
├── 📂 week1_wine_quality/
│   ├── README.md
│   ├── week1_analysis.ipynb
│   ├── streamlit_app.py
│   ├── requirements.txt
│   ├── models/
│   └── visualizations/
│
├── 📂 week2_churn_predictor/
│   ├── README.md
│   ├── week2_churn.ipynb
│   ├── streamlit_app.py
│   └── ...
│
├── 📂 week3_nlp_classifier/
│   ├── README.md
│   ├── week3_nlp.ipynb
│   ├── bert_model/
│   └── ...
│
├── 📂 week4_cv_detector/
│   ├── README.md
│   ├── week4_yolo.ipynb
│   ├── yolov8_model/
│   └── ...
│
├── 📂 week5_mlops/
│   ├── README.md
│   ├── fastapi_app/
│   ├── Dockerfile
│   └── ...
│
├── 📂 week6_dashboard/
│   ├── README.md
│   ├── streamlit_dashboard/
│   └── ...
│
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📄 README.md                          # This file
🚀 Quick Start
1. Clone Repository
bash
git clone https://github.com/yourusername/nexariza-ai-ml-internship.git
cd nexariza-ai-ml-internship
2. Setup Environment
bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
3. Run Any Week's Project
bash
# Week 1 — Wine Quality
cd week1_wine_quality
streamlit run streamlit_app.py

# Week 2 — Churn Predictor
cd week2_churn_predictor
streamlit run streamlit_app.py

# ...and so on
