# 🏡 Bangalore House Price Prediction - ML Web App

This is a complete end-to-end machine learning web application, **deployed on AWS**, that predicts property prices in Bangalore based on inputs like area (in square feet), number of bedrooms (BHK), bathrooms, and location.

The application integrates a trained ML model with a Flask-based backend and a responsive frontend built using HTML, CSS, and JavaScript. It is served via Nginx for a production-like setup on the cloud.

# Demo Video
![Image](https://github.com/user-attachments/assets/8a3f5b89-1bc9-43d8-8c17-64974f93abfb)

## 📌 Features

- 🧠 Machine Learning model trained on real Bangalore housing data
- 🔌 RESTful API using Flask (Python)
- 🧾 Frontend interface using HTML, CSS, and vanilla JavaScript
- 📡 AJAX-based communication between frontend and backend
- 🔁 Live location dropdown populated from the backend
- 📦 Model served using Pickle serialization
- 🧰 Reverse-proxy setup using Nginx (for production-like environment)

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **ML Library**: Scikit-learn, NumPy
- **Web Server**: Nginx
- **Serialization**: Pickle
- **Deployment Ready**: Nginx-compatible structure for serving

## ☁️ Deployed on AWS

- The application is hosted on an **Amazon EC2 instance** using **Flask** as the backend API and **Nginx** as the web server.
- All static files (HTML, CSS, JS) are served through Nginx.
- Flask runs on `localhost:5000` and Nginx proxies requests from port `80` to it.

🛡️ Make sure your EC2 instance:
- Has ports `80` (HTTP) and `5000` open (or just `80` if using Nginx)
- Has the Flask app running in the background (e.g., using `screen`, `nohup`, or `gunicorn`)

