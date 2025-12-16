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
