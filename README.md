# BookMyTicket

An Application to book movie tickets.  

## Description

The application has two users Theatre staff and users who book tickets. The theatre staff can Create, Update, Delete Movies and add Shows for each movie on any day. 
The end users can book tickets after creating an account. The application is developed using Django the database used is PostgreSQL. 

#### Flow of app names (dependency chain, for reference)
```
django-admin startproject movieticket
cd movieticket
django-admin startapp accounts
django-admin startapp staff
django-admin startapp booking
```
- add app names, 
- change default user model, to create custom user model
- change database configuration in .env file file.

## UI Preview

### User End / Customer / Booking App (gif @1fps)
![movie ticket project](https://user-images.githubusercontent.com/37036491/211182417-084e8044-2733-4272-ab7e-7c50ce8f5a89.gif)

### Admin End / Theatre Staff (gif @1fps)
![movie ticket project 2](https://user-images.githubusercontent.com/37036491/211182565-7e12ab00-0f85-448a-be37-76fd35195167.gif)


## Getting Started

### Dependencies

Python, Pip, Virtualenv, Django, Other (psycopg2-binary, crispy-bootstrap5, django-crispy-forms, psycopg2, python-dotenv)
```
pip install -r requirements.txt
```

### Running the program

```
Python manage.py runserver
```



# Movie-_Ticket_Booking
