# Green Guardian - Django Project(Team Bytedragon)


This project is a gamified learning platform for students and teachers focusing on environmental awareness.

## Setup Instructions

With Pip(recomend)
1. Create virtual environment:

```cmd
python -m venv venv_name
```

2. Activate virtual environment: > 

```cmd
venv_name\Scripts\activate
```

3. Install dependencies: > 

```cmd
pip install -r requirements.txt
```

4. Run server: > 

```cmd
python manage.py makemigrations
python manage.py migrate
python manage.py collectstatic
python manage.py runserver
```

With uv(fast)
1. Initialize UV: > 

```cmd
uv init
```

1. Create virtual environment: > 

```cmd
uv venv venv_name
```

2. Activate virtual environment: > 

```cmd
venv_name\Scripts\activate
```

3. Install dependencies: > 

```cmd
uv add -r requirements.txt
```

4. Run server: > 

```cmd
python manage.py makemigrations
python manage.py migrate
python manage.py collectstatic
python manage.py runserver
```


### Super User
User Name:User
Password:User1234


## Project Structure

- gamification/ : Django app
- venv_name/ : Virtual environment
- templates/ : HTML templates
- static/ : Game(Godot)

## Contribution

- Frontend:[Manthan Vizuda](https://github.com/Manthanvinzuda007)
- Game:[Utsav laheru
](https://github.com/UtsavLaheru)
