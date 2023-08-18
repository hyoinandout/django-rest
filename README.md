# django-rest

[![Build Status](https://travis-ci.org/hyoinandout/django-rest.svg?branch=master)](https://travis-ci.org/hyoinandout/django-rest)
[![Built with](https://img.shields.io/badge/Built_with-Cookiecutter_Django_Rest-F7B633.svg)](https://github.com/agconti/cookiecutter-django-rest)

ticket reservation app using celery and django. Check out the project's [documentation](http://hyoinandout.github.io/django-rest/).

# Motivation

On February 9th, I booked a ticket for a developer conference called [NAVER DEVIEW](https://deview.kr/2023). One interesting thing was that although I clicked a bit earlier than the exact ticket opening time (and, of course, if you try to enter the booking page earlier, you might fail to book the ticket), I was able to enter the booking page without waiting in a queue right after refreshing the web page. However, my colleagues who tried to book the ticket at the same time faced the queue and eventually failed to book the ticket. This made me curious about the server structure, which became the motivation for this project.

# Prerequisites

- [Docker](https://docs.docker.com/docker-for-mac/install/)  

# Local Development

Start the dev server for local development:
```bash
docker-compose up
```

Run a command inside the docker container:

```bash
docker-compose run --rm web [command]
```
