# FastAPI_Registration
FastAPI Registration - is a registration and login module built on FastAPI.

## Requirements
* Python
* FastAPI
* Uvicorn
* Sqlalchemy

## How to install?
1. Install the required libraries (listed above)
   
   FastAPI
   ```
   pip install fastapi
   ```
   Uvicorn
   ```
   pip install uvicorn
   ```
   Sqlalchemy
   ```
   pip install SQLAlchemy
   ```
2. Clone the repository

   ```
   git clone https://github.com/xok9ty/FastAPI_Registration.git
   ```
3. Create and activate the virtual environment

   ```
   python -m venv venv
   source venv\Scripts\activate
   ```
4.Install the dependencies

 ```
 pip install -r requirements.txt
 ```

## How to run the code?
Start the server with Uvicorn:

```
uvicorn main:app --reload
```
The application will be available at http://127.0.0.1:8000.

## The structure of the project
* main.py (The main application file that contains routes and logic.)
* templates/ (A directory containing HTML templates.)
