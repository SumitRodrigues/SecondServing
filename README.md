# SecondServing

**SecondServing** is a full-stack platform that connects food donors (like grocery stores and restaurants) with shelters and NGOs to reduce food waste and feed communities. It matches surplus food with real-time requests, intelligently verifies items, and fosters a circular food economy.

---

## 🚀 Features

- 🥫 **Post Surplus**: Donors can post excess food inventory with expiry details.
- 🧾 **Request Food**: Shelters can raise food requests by category and urgency.
- 🔁 **Matching logic**: Automatically matches food items with requests based on title, category, quantity, and urgency.
- 📊 **Dashboards**: Separate donor and shelter dashboards for managing stock, requests, and analytics.
- 📦 **Inventory & Request Management**: Track what's posted, matched, fulfilled, and expired.

---

## 🛠 Tech Stack

### 🔹 Frontend
- React + TypeScript
- TailwindCSS
- Axios for API calls

### 🔹 Backend
- FastAPI
- SQLAlchemy ORM
- Pydantic v2
- PostgreSQL

---

## 📦 Getting Started

### 📁 Clone the Repo

git clone https://github.com/SumitRodrigues/SecondServing.git
cd SecondServing

## Configure the backend
cd backend

### Create a virtual envioronment 
`python -m venv .venv`

### Create a .env file which has the DB details and the secret key for encryption with following keys
`DB_USER="postgres"
DB_PASSWORD=""
DB_HOST="localhost"
DB_PORT="5432"
DB_NAME="second-serving"
SECRET_KEY=""`

### Install all the dependencies
`pip install -r requirements.txt`

### Configure the database
`python script.py`

### Start the server
`uvicorn main:app --reload --port 8080`


## Start the frontend
cd secondServing-frontend

### Install the dependencies
`npm install`

### Start the server
`npm run dev`
