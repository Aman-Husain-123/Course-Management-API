# 📚 Course Management API (FastAPI + JSON Storage)

A simple **FastAPI-based REST API** that allows users to submit and store **course information** using a validated **Pydantic model**.  
The API accepts a **list of courses** and persists them into a **JSON file**, ensuring data integrity through validation rules.

---

## 🚀 Features

- ✅ Pydantic model for course validation
- ✅ Accepts **multiple course records** in a single request
- ✅ Stores data in a local JSON file
- ✅ Input validation for:
  - Positive course ID
  - Valid credit range
  - Non-empty strings
- ✅ Interactive Swagger UI

---

## 🛠️ Tech Stack

- **Backend Framework:** FastAPI
- **Validation:** Pydantic
- **Server:** Uvicorn
- **Storage:** JSON file (file-based persistence)
- **Language:** Python 3.9+

---

## 📂 Project Structure

``
.
- ├── index.py # FastAPI application
- ├── courses.json # Auto-generated JSON storage
- ├── README.md # Project documentation
- └── requirements.txt # Project dependencies




---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Aman-Husain-123/neon_db_API_testing.git
cd neon_db_API_testing

---

2️⃣ Create Virtual Environment (Optional but Recommended
python -m venv venv
source venv/bin/activate      # Linux / macOS
venv\Scripts\activate         # Windows

---

3️⃣ Install Dependencies
pip install -r requirements.txt

---

▶️ Run the Application
python -m uvicorn index:app --reload

Server will start at:
http://127.0.0.1:8000

--- 

📖 API Documentation (Swagger)

Open in browser:
http://127.0.0.1:8000/docs

