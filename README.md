🩺 Smart Healthcare Recommendation System with Analytical Visualization

An AI-powered web application that predicts an individual's health risk level and provides personalized healthcare recommendations based on lifestyle and vital data.
The system also includes an analytics dashboard that visualizes key health trends using data visualization techniques.

🚀 Features

🧠 Predicts health status (Healthy / Moderate / High Risk)

💡 Provides personalized diet, exercise, and lifestyle tips

📊 Displays BMI, Age, Glucose, and Activity visualizations

🌐 Simple and interactive web interface

⚙️ Machine Learning integrated with Flask backend

🧰 Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: Flask (Python)
Machine Learning: Scikit-learn, Pandas, NumPy
Visualization: Matplotlib, Seaborn

⚙️ Installation

Clone the repository

git clone https://github.com/dudalalikithasri19/Smart-Healthcare-Recommendation-System-with-Analytical-Visualization.git
cd Smart-Healthcare-Recommendation-System-with-Analytical-Visualization


Create & activate virtual environment

python -m venv .venv
.venv\Scripts\activate


Install dependencies

pip install -r requirements.txt


Run the Flask backend

cd backend
python app.py


Start the frontend

cd frontend
python -m http.server 5500


Open in browser → http://127.0.0.1:5500

📊 Data Analytics

Run the following command to generate visualizations:

cd ml
python analytics.py


All charts (BMI, Age, Glucose, Correlation, etc.) will be saved and displayed in the frontend analytics dashboard.

🏁 Conclusion

This system combines AI + Analytics to promote preventive healthcare, enabling users to make better and healthier decisions.
