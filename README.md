# CarRentPy
Successful car rental app on Python, with SQL database.
## Car rental shop app with made up prices.

Code was made using Python 3.13 with help of libraries such as PyQt6 for GUI and sqlite3 for DB implementation.

## Start-up
```Python
pip isntall pyinstaller
pyinstaller --onefile --windowed main.py
```
You have to put cars database inside the exe file, as well as resources folder which has a stock.jpg image.

### Structure
#### cars
```
id INTEGER
name TEXT
brand TEXT
year INTEGER
cost INTEGER
info TEXT
image_path TEXT
is_rented INTEGER
```
#### users
```
id INTEGER
login TEXT
password TEXT
isadmin BOOLEAN
```

## Description
UI to rent cars. There are 2 roles of users: administrators that can to edit car information, edit list of available cars, edit clients. Regular user or client can look for cars in a catalogue as well as book a car for rent.
