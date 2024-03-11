# python-flask-docker

A sample app to demonstrate containerizing a Python Flask application.

[Docker's Python Language Guide](https://docs.docker.com/language/python).

## Insructions
1. build the docker file

```docker build -t python-flask-docker .```

2. run the docker container

```docker run -d -p 5000:5000 --name "python-flask-docker" python-flask-docker```

3. access the containerized flask app on the host at the mapped port 5000
http://localhost:5000 OR http://127.0.0.1:5000
