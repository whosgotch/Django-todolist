# Django-ToDoList
[To Do list app](https://whosgotch.pythonanywhere.com/) with User Registration, Login, Search and full Create Read Update and DELETE functionality.
</br>
<p align="center">
   <img src="../master/todolist.png" alt="something went wrong...">
</p></br>

## How to run Django-ToDoList on your computer

- Installation of the required files 
- Creating virtual environment
- Running Django ToDoList on local host

### step 1
1 - Download [Python 3.9+](https://www.python.org/) and install it.

**OR**

Install using *scoop*.
```
> scoop install python
```

2 - Check Python version
```
> python --version
Python 3.11.1
```

3 - Install virtualenv with pip install
```
> pip install virtualenv
```

### step 2
1 - Create virtual environment using virtualenv
```
> python -m virtualenv venv
```

2 - Activate virtual environment
```
> venv/scripts/activate
```

3 - Install Django using pip install
```
(venv) > pip install django
```

### step 3 
1 - Make a git clone of Django ToDoList to your project folder
```
(venv) > git clone https://github.com/whosgotch/Django-ToDoList.git
```

2 - Open project folder with console and run server
```
(venv) > cd Django-ToDoList
(venv) > python manage.py runserver

Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
February 05, 2023 - 20:10:14
Django version 4.1.6, using settings 'todo_list.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

```

3 - Copy 127.0.0.1:8000 and paste it into your browser search bar.


