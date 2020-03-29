# MyWeb
I develop my personal web site with Flask.

# Run app 

-You need docker "https://www.docker.com/"


Ensure you have Docker installed in your system.

-First we build the docker-compose


$ docker-compose build  

You should get an output like this:

...
Step 1/5 : FROM python:3.8-slim-buster
3.8-slim-buster: Pulling from library/python
...

...
---> a1c95d6a940f
Successfully built a1c95d6a940f
Successfully tagged corta_urls_web:latest
...


-Second run the server in background, and
conect your host at Flask-server


$ docker-compose up -d


You should get an output like this:

Creating my-web_web ... done


## Starting the application

To run the application, open a terminal and call `docker-compose run` migrate your data base and using the port `0.0.0.0:8000`


$ docker-compose run web


welcome to corta_urls.

## Starting the test

$ docker-compose run test

