# zadanie1
-w CMD wpisuje te komendy:
w cmd wpisałam komendy
mkdir FlaskApp
cd FlaskApp
py -3 -m venv venv
venv\Scripts\activate
pip install Flask
-tworze plik w PyCharm z nazwa flaskapp.py i wklejam do niego:
from flask import Flask

 app = Flask(__name__)

 @app.route("/")
 def hello_world():
 	return "<p>Hello, World!</p>"
  -Zapisuje plik
  -w CMD wpisuje komende:
  set FLASK_APP=flaskapp.py
  -w CMD uruchamiam aplikacje komenda:
  flask run
  -kopiuje z CMD adres do przeglądarki sprawdzić czy link zadziała i pokaże - "Hello, World!"
  -w CMD zapisuje liste komenda:
  pip freeze > requirements.txt
