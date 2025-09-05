CareerPathAI – ML-Based Career Recommender System

CareerPathAI is a machine learning–based recommendation engine that suggests personalized study and career paths for students.
It processes academic data, applies ML models, and delivers actionable recommendations via a Flask web app.

Features
Personalized career path suggestions.
Academic data preprocessing & feature engineering.
Multiple ML models tested (Random Forest, Logistic Regression, etc.).
Flask web app for deployment.
Detailed recommendations with insights and graphs.


Tech Stack
Language: Python
Libraries: Scikit-learn, Pandas, NumPy, Matplotlib
Framework: Flask


⚙️ Installation & Setup
# Clone repository
git clone https://github.com/<your-username>/careerpathai.git
cd careerpathai

# Virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Run Flask app
python app.py