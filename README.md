# docker-django-app

This is a simple Django web app ready to be containerised.
The container will expose your application on port `8000`

## How-to
* To build an image use the following command
```
docker build --tag django_docker:latest .
```
* To run your container 
```
docker run --name django_docker -d -p 8000:8000 django_docker:latest
