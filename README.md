# DVMN Watching Storage

The code is written for educational purposes on online-course for web-developers [dvmn.org](https://dvmn.org/).

### How to install

- Python3 should be already installed. 
- Then use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```
pip install -r requirements.txt
```
- Set up environment variables with your DB credentials and other settings
```
DB_ENGINE=django.db.backends.postgresql_psycopg2
DB_HOST=examle.org
DB_PORT=5434
DB_NAME=db_name
DB_USER=user
DB_PASSWORD=password
DEBUG=True
SECRET_KEY=secret_key
```
- Start the server
```
python manage.py runserver 8000
```
- Open http://127.0.0.1:8000/ in your browser