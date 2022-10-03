# how-to-make-python-localhost-

# 1. Make Sure use this command to install Sanic

# 2. Code Down Here!

```
from sanic import Sanic
from sanic.response import text

app = Sanic("MyHelloWorldApp")

@app.get("/")
async def hello_world(request):
    return text("Hello, world.")


if __name__ == "__main__":
    app.run(host="localhost", port=69)  
