Package install 
```
pip3 install -r requirements.txt
```

Using server
```
# Create DB
$python3 do_db.py
# Using
$python3 manage.py runserver
```
### nohub
```
$ mkdir ./log/
$ nohub python3 manage.py runserver >> ./log/flask.log
```
Delete DB
```
$rm adsen/adsen.db 
```
