# FastAPI Issue Tracker

A simple REST API built using FastAPI to manage and track issues. Users can create, retrieve, update, and delete issues through a clean and well-documented API.

## 🚀 Live Demo

**API Service**

https://fast-api-issue-trackerr.onrender.com

**Swagger Documentation**

https://fast-api-issue-trackerr.onrender.com/docs

To test the API:

1. Open the Swagger Docs link above.
2. Select any endpoint.
3. Click **Try it out**.
4. Enter the required data.
5. Click **Execute** to send the request.

---

## ✨ Features

* Create Issues
* Retrieve All Issues
* Retrieve Issue by ID
* Update Existing Issues
* Delete Issues
* UUID-based Unique IDs
* Request Validation using Pydantic
* Interactive Swagger Documentation
* JSON-based Data Storage

---

## 🛠️ Tech Stack

* FastAPI
* Python
* Pydantic
* Uvicorn
* JSON Storage

---

## 📌 Available Endpoints

| Method | Endpoint                    | Description        |
| ------ | --------------------------- | ------------------ |
| GET    | `/api/v1/issues`            | Get all issues     |
| GET    | `/api/v1/issues/{issue_id}` | Get issue by ID    |
| POST   | `/api/v1/issues`            | Create a new issue |
| PUT    | `/api/v1/issues/{issue_id}` | Update an issue    |
| DELETE | `/api/v1/issues/{issue_id}` | Delete an issue    |

---

## 📝 Example Request

### Create Issue

```json
{
  "title": "Login Bug",
  "description": "Users are unable to log in.",
  "priority": "high"
}
```

---

## 💻 Run Locally

### Clone Repository

```bash
git clone https://github.com/aryan2006-saini/fast-api-issue-tracker.git
cd fast-api-issue-tracker
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Virtual Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Server

```bash
uvicorn main:app --reload
```

### Open Swagger Docs

```text
http://127.0.0.1:8000/docs
```

---

## 📂 Project Structure

```text
fast-api-issue-tracker/
│
├── main.py
├── requirements.txt
│
└── app/
    ├── schemas.py
    ├── storage.py
    └── routes/
        └── issues.py
```

---

## 🌐 Deployed Application

Service URL:

https://fast-api-issue-trackerr.onrender.com

Swagger UI:

https://fast-api-issue-trackerr.onrender.com/docs

---

## 👨‍💻 Author

Aryan Saini

GitHub: https://github.com/aryan2006-saini
