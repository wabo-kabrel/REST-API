# Flask REST API

This is a simple REST API built with **Flask**, **Flask-RESTful**, and **Flask-SQLAlchemy**. It allows basic CRUD operations on users with `name` and `email` fields using an SQLite database.

---

## Project Files

- `api.py`: Main API logic
- `create_db.py`: Script to create the database
- `requirements.txt`: Lists all required Python packages
- `database.db`: Auto-created database after running `create_db.py`

---

## How to Run This Project

Follow these steps to set up and run the API locally.

---

### Step 1: Create a Virtual Environment

Open your terminal and run:

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate


### Step 2: Install Dependencies
Run:

pip install -r requirements.txt


### Step 3: Create the Database
Run:

python create_db.py


### Step 4: Run the API
Run:
python api.py

By default, the app will be running at:
http://127.0.0.1:5000/

---

## API Endpoints

### Create a User:
POST /api/users/

### Get All Users:
GET /api/users/

### Get a Single User:
GET /api/users/<id>

### Update a User:
PATCH /api/users/<id>

### Delete a User:
DELETE /api/users/<id>




