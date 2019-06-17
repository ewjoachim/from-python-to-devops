# From Python to DevOps

In this repo, we try to gather short tutorials and follow up resources on many important subjects for software and python proficient people to learn web development, and deployment.

## Disclaimers, assumptions, constraints

Here are explicit constraints and assumptions that will guide our writing:

- Should fit withing 2 weeks full-time (6h a day, 5 days a week), so this means up to 60h of work.
- The assumption is that the target learner prefers to get a basic understanding and theory first, then do exercices. Every learner is different, though.
- The learner already confortable around Python, shell, and development in general (git, ...). For example, they're Data Scientist, it's just that they never did web development in particular. In fact, we'll assume they're Machine Learning specialist, trying to expose their work through a web interface.
- This curriculum is being prepared for a specific learner in mind. We may skip important things that we trust they already know, and make different adaptations. That being said, there's not reason thois would not benefit other individuals in a similar situation.
- The aim is not to become "proficient" in everything but to demistify it and provide resources for further learning. Also, we're heading towards a "backend devops" idea, with a sprinkle of front end. Not full stack.

## Table of contents

1. Web and HTTP
    1. TCP & HTTP
    1. HTTP Protocol: Requests & Response, URLs, Verbs, Status Codes, Headers, Bodies, Content Types
    1. Browsers and HTTP, browser inspector
    1. Websites, Server side vs Ajax vs SPA
    1. HTTP APIs, REST / RPC
    1. HTTP clients (requests, curl, Postman/Insomnia/...)
    1. CSS
    1. Javascript
    1. Security: HTTPS, security headers, XSS
    1. DNS
    1. HTTP2
    1. Authentication, Cookies and JWT
1. Web and Python
    1. CGI, WSGI, Gunicorn/uwsgi (and ASGI)
    1. Flask (/Pyramid)
    1. Django (on the web side)
    1. Async: Aiohttp / ASGI
    1. Nginx and edge proxy
1. Task queues
    1. A classic backend: RabbitMQ (also, Redis, Kafka...)
    1. Celery (flower)
    1. Dramatiq, ...
1. Database
    1. Postgres, Psycopg
    1. SQL Injections
    1. Transactions
    1. ORM. Django (on the models side)
1. Unix, processes, etc
    1. Unix concepts: Users, Processes, Exit codes, Signals, Env vars, Streams & redirections
    1. Bash
    1. SystemD, systemctl, journalctl
1. Devops
    1. DevOps, InfrastructureAsCode
    1. Monitoring
    1. Logging (Python logging, standard streams, rsyslog, structured logging)
    1. Error handling
    1. Load balancing, ZDD
    1. Ansible
    1. Vault
    1. 12-factors
    1. "Cloud"
    1. Docker, Kubernetes/
    1. PythonAnywhere
    1. S3 / Amazon Lambda
1. Dev environment
    1. Setuptools
    1. Virtualenv, Pipenv, poetry, lock files
    1. Linters and formatters, mypy
    1. Tox
    1. TravisCI & CircleCI
    1. Docker compose

## Licence, contributions etc.

This repo is published on the public domain (CC0).

All additions, from typos to new sections, are welcomed through Pull Requests. Contributions include full adhesion to the [Contributor Covenant](https://www.contributor-covenant.org/version/1/4/code-of-conduct), any inquiry can be send to the repo owner email (first name at last name dot fr, or check of his commits)
