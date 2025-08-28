✅ TodoFlow

A modern and simple Flask-based To-Do application with authentication and task management.  
Built as a project demo to showcase Flask, SQLite, and password hashing with bcrypt.  


 🚀 Features
- User Registration & Login (with hashed passwords using bcrypt 🔒)
- Add, view, and manage your tasks
- Separate sections for:
  - 📝 Pending Tasks
  - ✅ Completed Tasks
  - ➕ Recently Added Tasks
- Modern UI with Dynamic Island-style top bar
- Flash messages for user feedback
- Lightweight SQLite database (no setup required)



🛠️ Tech Stack
- [Flask](https://flask.palletsprojects.com/) – Web framework
- [SQLite](https://www.sqlite.org/index.html) – Lightweight database
- [bcrypt](https://pypi.org/project/bcrypt/) – Secure password hashing
- HTML5, CSS3, Jinja2 Templates – Frontend



📂 Project Structure
todo_app/
│── app.py            # Main Flask application
│── requirements.txt  # Dependencies
│── templates/        # HTML templates (base, login, register, todo)
│── static/           # CSS and JS files
│── instance/
│    └── todo.db      # SQLite database (auto-created)

</>Create a virtual environment(optional but highly recomemded)
-python -m venv venv
-source venv/bin/activate   # On Linux/Mac
-venv\Scripts\activate      # On Windows

</>Install Dependencies
pip install -r requirement.txt

Run the App
-flask run

Built out of boredom by hismajesty404
