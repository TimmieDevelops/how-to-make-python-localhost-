# how-to-make-python-localhost-

# 1. Make Sure use this command to install Flask

# 2. Code Down Here!

```
from flask import Flask

app = Flask(__name__)

@app.route("/")
def main():
    return "Hello Welcome!"

if __name__ == "__main__":
    app.run(debug=True, host="0.0.0.0", port=7000)```
