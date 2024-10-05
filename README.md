1. Open the Project in IDE.
2. Set Up the Python Environment: If you haven't already, make sure you have Python installed on your system.
3. Open the terminal in IDE .
4. Create a virtual environment (if needed):python -m venv venv
5.Activate the virtual environment:
  On macOS/Linux: source venv/bin/activate
  On Windows:venv\Scripts\activate
6. Install Dependencies as specified in requirements.txt document.
7. Run Database Migrations : Set up the database, run: python manage.py migrate
8. Run code: python manage.py runserver
