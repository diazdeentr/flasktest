# flasktest
## Pruebas de Flask
### Primer prgrama : Hello World

```
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"

if __name__ == "__main__":
    app.run()
```

How to setup flask : [http://flask.pocoo.org/](link)
