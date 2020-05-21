## Diatoz Applied AI team - Knowledge Base



Instructions to add resources:

1. Contents

   - Text 

     - Contextual details 

   - Code

     - Sample snippets

   - Hyperlinks

   - Videos

     - iframe - youtube videos

       

2. Important Notice

3. Interesting Facts

4. Reference links

   

## Flask

[Flask](https://palletsprojects.com/p/flask/) is a lightweight [WSGI](https://wsgi.readthedocs.io/) web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around [Werkzeug](https://palletsprojects.com/p/werkzeug) and [Jinja](https://palletsprojects.com/p/jinja) and has become one of the most popular Python web application frameworks.


```
from flask import Flask, escape, request

app = Flask(__name__)

@app.route('/')
def hello():
    name = request.args.get("name", "World")
    return f'Hello, {escape(name)}!'
```

```
$ env FLASK_APP=hello.py flask run
 * Serving Flask app "hello"
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```



#### Important Notice:

`While lightweight and easy to use, **Flask’s built-in server is not suitable for production** as it doesn’t scale well. Some of the options available for properly running Flask in production are documented here.`

`If you want to deploy your Flask application to a WSGI server not listed here, look up the server documentation about how to use a WSGI app with it. Just remember that your Flask application object is the actual WSGI application.`



<iframe width="560" height="315" src="https://www.youtube.com/embed/Z1RJmh_OqeA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



Reference links:

https://flask.palletsprojects.com/en/1.1.x/deploying/

