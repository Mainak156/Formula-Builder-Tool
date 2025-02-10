#🧮 Formula Builder Tool - Price Calculations
##📌 Overview
The Formula Builder Tool is a full-stack web application that enables users to create, manage, and apply formulas for price calculations dynamically. The tool allows users to store predefined formulas, apply them to sales data, and view results in real-time.

##🏗 Tech Stack
Backend: Python, Flask, Flask-SQLAlchemy, Flask-Migrate, Flask-CORS
Database: MySQL
Frontend: React.js, Tailwind CSS
Other Tools: SQLAlchemy ORM, Axios (API calls), Context API (state management)

##⚙ Features
✅ User-Friendly UI – React-based intuitive interface for formula management
✅ Dynamic Formula Builder – Create, edit, and delete formulas dynamically
✅ Sales Data Management – Store and retrieve structured sales data
✅ Live Formula Execution – Apply formulas and calculate results instantly
✅ Secure API Backend – Flask-based REST API with database integration
✅ Persistent Storage – Data stored in MySQL with proper schema

##📂 Project Structure
Formula-Builder-Tool/
├── backend/              # Flask API
│   ├── migrations/       # Database migrations
│   ├── app.py           # Main Flask app
│   ├── config.py        # App configuration
│   ├── db.py            # SQLAlchemy DB connection
│   ├── models.py        # Database models
│   ├── formulas.py      # Formula processing logic
│   ├── requirements.txt # Dependencies
├── frontend/             # React.js Frontend
│   ├── src/
│   │   ├── components/   # UI Components
│   │   ├── App.js       # Main React App
│   │   ├── index.js     # Entry point
│   │   ├── styles.css   # Global styles
│   ├── package.json     # Dependencies
├── README.md            # Project Documentation
├── .gitignore           # Ignore unnecessary files
🚀 Setup & Installation
🔹 Backend Setup (Flask)

##1️⃣ Navigate to the backend folder:
cd backend

##2️⃣ Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

##3️⃣ Install dependencies:
pip install -r requirements.txt

##4️⃣ Set up the database:
flask db init
flask db migrate -m "Initial migration"
flask db upgrade

##5️⃣ Run the Flask server:
python app.py

##🔹 Frontend Setup (React)
##1️⃣ Navigate to the frontend folder:
cd frontend

##2️⃣ Install dependencies:
npm install

##3️⃣ Start the React app:
npm start

##🎯 How It Works
1️⃣ Add Formulas – Define formulas using dynamic fields
2️⃣ Store Data – Add sales-related data (like product price, quantity)
3️⃣ Apply Formulas – Compute final values using predefined formulas
4️⃣ View Results – See live calculations instantly on the frontend
