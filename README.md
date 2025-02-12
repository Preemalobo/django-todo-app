Please note that the branch name is Main not main.

# ToDo Django Project  

A simple To-Do application built with Django. Users can add, edit, and delete tasks.  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Preemalobo/django-todo-app.git
   cd django-todo-app

2.Create and activate a virtual environment:

python -m venv .venv
source .venv/bin/activate  # Mac/Linux
.venv\Scripts\activate     # Windows

3.Install dependencies:

pip install -r requirements.txt

4.Apply migrations:

python manage.py migrate

5.Create a superuser:

python manage.py createsuperuser

6.Run the server:

python manage.py runserver


#### 4️⃣ **Features**  
```markdown
## Features  
- Add, update, and delete tasks  
- Django Admin Panel  
- SQLite database  
- Bootstrap for UI


## Project Structure
your-repo-name/  
│── manage.py  
│── db.sqlite3  
│── .venv/  
│── To_Do/  
│   ├── models.py  
│   ├── views.py  
│   ├── urls.py  
│   ├── templates/  
│── requirements.txt  
│── .gitignore  
│── README.md  


## Technologies Used  
- Python 3.x  
- Django 4.x  
- SQLite  
- Bootstrap  

