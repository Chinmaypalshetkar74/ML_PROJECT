# ML_Project
https://fwi-ml-project.onrender.com/

🔥 End-to-End Machine Learning Project: FWI (Fire Weather Index) Prediction Web App
✅ Deployed with Streamlit | 🌐 Hosted on Render | 📦 Code & Dataset on GitHub
📍 Dataset Used: Algerian Forest Fire Dataset

📌 Project Overvie
This project is a real-time Fire Weather Index (FWI) prediction app built using machine learning models and the Algerian Forest Fire Dataset. It forecasts the fire risk level based on weather conditions such as temperature, humidity, wind speed, and rainfall. Users can interactively enter values and instantly get predictions through a clean web interface.

🎯 Project Objective
To create a fully functional ML pipeline and deploy an accessible web app that provides wildfire risk prediction, helping demonstrate how AI can support environmental monitoring.

🧠 Tech Stac
🐍 Language: Python
📦 Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-lear
🤖 ML Models: Linear, Lasso, Ridge, ElasticNet Regression
🎨 Frontend UI: Streamlit
🚀 Deployment Platform: Render
💻 Version Control: GitHub

📊 Model Performance (R² Score / MAE)

🧪 Model	📈 R² Score	📉 MAE

Linear	0.9497	0.6149
Lasso	0.9675	0.4924
ElasticNet	0.9801	0.3722
✅ Ridge	0.9842	0.3610 ✅

👉 Ridge Regression was selected for deployment as it delivered the highest accuracy on unseen test data.
🖥 Live Web App

🌐 Try out the deployed app here:
🔗 [Add your Render app link]
💾 GitHub Repository

Full codebase, dataset, and preprocessing pipeline:
🔗 https://github.com/yourusername/fwi-prediction

🔁 Project Pipeline
1. 🧹 Data Cleaning & Preparation
2. 📊 EDA & Correlation Analysis
3. 🔄 Feature Encoding (OHE for categorical columns)
4. 🧠 Model Training & Evaluation
5. 🧪 Model Comparison
6. 🖼 UI Building with Streamli
7. 🚀 Model Deployment on Render
8. 🗂 Source Control & Documentation on GitHu
⚙ Scalability & Improvement

✅ Current Solution
The dataset contains categorical text features such as Region and Classes, which ML models can't process directly.
I applied One-Hot Encoding (OHE) to convert these into numerical format.
🔮 Planned Upgrades:

🔄 Add support for mixed input types (float + text).
The app will automatically convert text to numbers using built-in encoding. In the future, I’ll explore smarter techniques like target encoding, label encoding, or even embedding layers to support more flexible input.
📁 Upcoming Features:
CSV Upload for batch predictions 📤
Visualized Model Comparison 📊
Feature Importance Dashboard 💡
Add advanced ML models like Random Forest, XGBoost 🌲
Expand model training to international forest datasets for better generalization 🌍

💡 I'm also exploring ways to automatically detect and process text inputs in real-time, so users don’t need to worry about formatting.
🌟 Key Learning
✔ Built a full ML pipeline from scratch
✔ Implemented multiple regression models & selected the best using R²/MAE
✔ Developed a front-end interface using Streamlit
✔ Learned to host ML models using Render
✔ Strengthened practical skills in model deployment & reproducibility

🧠 This project is a step toward making AI solutions accessible, even for non-technical users. It demonstrates how machine learning can help tackle real-world challenges — like predicting and preventing wildfire damage.
🤝 Feel free to try the app, explore the code, or reach out for collaboration, feedback, or improvement ideas
🔖 #Hashtags for Visibility
#MachineLearning #DataScience #Streamlit #Python #MLDeployment #RegressionModels #ForestFirePrediction #WildfireRisk #AIForGood #GitHub #RidgeRegression #DataSciencePortfolio #EnvironmentalAI #OpenSource
