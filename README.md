# Web-ChatApp 
This is a guide for installing a web chat application that has been developed using react.js, django-rest-framework, and django-signal.

# Installation Process
You can install this app by following steps below.

### Running Backend
```
1. Create a virtual environment: `virtualenv venv`
2. Activate the virtual environment:
    For Linux: `source venv/bin/activate`
    For Windows: `venv\Scripts\activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Migrate to the database: `python manage.py migrate`
5. Run the server: `python manage.py runserver`
```
### Running Front-end
```
1. Navigate to the 'clients/' directory: `cd clients\`
2. Install dependencies: `npm install`
3. Start the server: `npm start`
```

You can access the application on 'localhost:3000' or '127.0.0.1:3000'. Sign up with your name, email, and profile image, and start chatting from two different browser windows.
