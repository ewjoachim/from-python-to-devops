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

0. Web and HTTP
    0. TCP & HTTP
    0. HTTP Protocol: Requests & Response, URLs, Verbs, Status Codes, Headers, Bodies, Content Types
    0. Browsers and HTTP, browser inspector
    0. Websites, Server side vs Ajax vs SPA
    0. HTTP APIs, REST / RPC
    0. HTTP clients (requests, curl, Postman/Insomnia/...)
    0. CSS
    0. Javascript
    0. Security: HTTPS, security headers, XSS
    0. DNS
    0. HTTP2
    0. Authentication, Cookies and JWT
0. Web and Python
    0. CGI, WSGI, Gunicorn/uwsgi (and ASGI)
    0. Flask (/Pyramid)
    0. Django (on the web side)
    0. Nginx and edge proxy
0. Task queues
    0. A classic backend: RabbitMQ (also, Redis, Kafka...)
    0. Celery (flower)
    0. Dramatiq, ...
0. Database
    0. Postgres, Psycopg
    0. SQL Injections
    0. Transactions
    0. ORM. Django (on the models side)
0. Unix, processes, etc
    0. Unix concepts: Users, Processes, Exit codes, Signals, Env vars, Streams & redirections
    0. Bash
    0. SystemD, systemctl, journalctl
    0. Docker
0. Devops
    0. DevOps, InfrastructureAsCode
    0. Monitoring
    0. Logging (Python logging, standard streams, rsyslog, structured logging)
    0. Error handling
    0. Load balancing, ZDD
    0. Ansible
    0. Vault
    0. 12-factors
    0. "Cloud"
    0. PythonAnywhere
    0. S3 / Amazon Lambda
0. Dev environment
    0. Setuptools
    0. Virtualenv, Pipenv, poetry, lock files
    0. Linters and formatters, mypy
    0. Tox
    0. TravisCI & CircleCI
    0. Docker compose

## Licence, contributions etc.

This repo is published on the public domain (CCO).

All additions, from typos to new sections, are welcomed through Pull Requests. Contributions include full adhesion to the [Contributor Covenant](https://www.contributor-covenant.org/version/1/4/code-of-conduct), any inquiry can be send to the repo owner email (first name at last name dot fr, or check of his commits)
