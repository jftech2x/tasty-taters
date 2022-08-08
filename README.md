# Tasty-Tater
```
Tasty-Taster , with a frontend built in React & Redux and a backend built in Django API.
This is an online food menu service for Tasty Taster. When you visit the restaurant, you often
use the QR code to load the PDF of the menu. It has no image and is not easy to select.
So we created the menu app where you can see food images with the needed information and
select your items easily. During such an unprecedented time and social distancing, online menu card technology is a boon!

```
Check out [FRONTEND LIVE DEMO](https://tasty-taster-frontend.herokuapp.com/) here!!
Check out [API LIVE DEMO](https://tasty-taster-backend.herokuapp.com) here!!
## Tech used
```
* Frontend : React & Redux
* Backend : Django
```
## How to Install
1. Git Clone https://github.com/crossincrono/Tasty-Taster.git
```
git clone 
```
2. Backend setting
```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/
```
3. Frontend setting
```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
