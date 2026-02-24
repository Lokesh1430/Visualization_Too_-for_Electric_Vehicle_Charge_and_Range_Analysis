🚗 Electric Cars Analytics Dashboard
<p align="center"> Visualization Tool for Electric Vehicle Charge & Range Analysis </p> <p align="center"> <img src="https://img.shields.io/badge/Python-Flask-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/Tableau-Visualization-orange?style=for-the-badge"> <img src="https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"> </p>
📑 Table of Contents

📌 Project Overview

🎯 Objectives

🏗️ System Architecture

🛠️ Technology Stack

📊 Dashboard Components

📖 Story Insights

🌐 Live Demo

🖼️ Screenshots

📂 Project Structure

🚀 Run Locally

✨ Features

📈 Future Scope

👨‍💻 Team Members

📜 License

📌 Project Overview

The Electric Cars Analytics Dashboard is an end-to-end data visualization system that analyzes electric vehicle efficiency, pricing, charging infrastructure, and brand distribution.

The project combines:

✔ MySQL Workbench for database storage
✔ Tableau Desktop Public for visualization
✔ Tableau Public for publishing
✔ Flask Web Application for deployment

It transforms raw EV datasets into interactive dashboards and storytelling analytics.

🎯 Objectives

Analyze EV performance and efficiency

Compare EV prices and models in India

Visualize charging station distribution

Create interactive Tableau dashboards

Deploy dashboards through Flask integration

🏗️ System Architecture
MySQL Database → Tableau Desktop → Tableau Public → Flask Web App → End User
Architecture Flow

1️⃣ Import CSV dataset into MySQL Workbench
2️⃣ Connect Tableau Desktop to MySQL
3️⃣ Create Sheets → Dashboard → Story
4️⃣ Publish to Tableau Public
5️⃣ Embed into Flask Website

🛠️ Technology Stack
Tool	Purpose
Tableau Desktop Public	Visualization
Tableau Public	Dashboard Publishing
MySQL Workbench	Database
Flask (Python)	Web Integration
HTML/CSS	Frontend
📊 Dashboard Components

🌍 Global Summary Card

🇮🇳 India Summary Card

🔵 Brands according to BodyStyle (Packed Bubble)

📊 Top 10 Efficient EV Brands (Bar Chart)

🥧 Brand Filtered by PowerTrain (Pie Chart)

🟩 Different EV Cars in India (Treemap)

⚡ Top Speed Comparison

📖 Story Insights

The Tableau Story provides guided analysis:

🗺️ EV Charging Stations Map of India
📊 Charging Stations by Region & Type
💰 Price Comparison of EV Cars
🚘 Number of Models by Brand

🌐 Live Demo

🔗 Live Flask Website
https://smartinternz-web-integration.onrender.com/

🔗 Tableau Public Dashboard
(Add your Tableau Public link here)

🖼️ Screenshots
📊 Electric Cars Analytics Dashboard

Add Dashboard Screenshot Here

📖 Story of Electric Cars in India

Add Story Screenshot Here

📂 Project Structure
Electric-Cars-Analytics/
│
├── flask_app/
│   ├── app.py
│   ├── templates/
│   └── static/
│
├── dataset/
│   └── ev_data.csv
│
├── tableau_files/
│   └── dashboard.twbx
│
└── README.md
🚀 Run Flask App Locally
git clone <your-repo-link>
cd Electric-Cars-Analytics
pip install flask
python app.py

Open browser:

http://127.0.0.1:5000
✨ Key Features

✔ Interactive Tableau Dashboards
✔ Story Navigation
✔ MySQL Data Connectivity
✔ Flask Web Deployment
✔ Clean UI Design
✔ Academic Project Architecture

📈 Future Scope

Real-time EV API integration

AI-based prediction models

Mobile-responsive dashboard

Advanced Python analytics

👨‍💻 Team Members

Team Leader
Naganaboyina Lakshmana Swamy

Team Members

Myla Venkaiah

Sangeetham Ganesh

Lokesh Pilla

📜 License

This project is developed for academic and educational purposes.
