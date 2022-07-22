# django_boilerplate_generator

An OS-agnostic environment for generating Django boilerplates

## Modules
* [Cookiecutter Django](https://github.com/cookiecutter/cookiecutter-django)
* [Docker/Docker-Compose](https://www.docker.com/)

## Basic Wirkflow
1) Activate Django Cookiecutter, answer questions to generate project
2) A folder is generated containing all related django/docker files
3) Copy files into new repository

```
docker-compose build; docker-compose run --rm boilerplate_generator cookiecutter https://github.com/cookiecutter/cookiecutter-django
```
