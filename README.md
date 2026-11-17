
# TaskManager - Django Background Processing

A practical backend project built using Django, Django REST Framework,
PostgreSQL, Redis and Celery.

## Technology Stack

- Python
- Django
- Django REST Framework
- PostgreSQL
- Redis
- Celery
- Celery Beat
- Docker and Docker Compose
- Git and GitHub

## Project Objectives

Build a TaskManager application that supports:

1. Task creation and management through REST APIs.
2. Persistent storage using PostgreSQL.
3. Background processing using Celery.
4. Redis as the Celery message broker.
5. Scheduled jobs using Celery Beat.
6. Task monitoring, retries and caching.
7. Docker-based deployment preparation.

## Local Development Setup

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd Redis_Celery
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate it on Windows

```cmd
venv\Scripts\activate
```

### 4. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Configure environment variables

Copy `.env.example` to `.env` and configure your local values.

Never commit `.env` or actual credentials.

### 6. Run Django checks

```bash
python manage.py check
```

### 7. Start Django

```bash
python manage.py runserver
```

## Development Roadmap

- [x] Initial Django project setup
- [x] Git repository initialization
- [ ] PostgreSQL integration
- [ ] Redis integration
- [ ] Celery background tasks
- [ ] REST API development
- [ ] Celery Beat scheduling
- [ ] Monitoring and testing
- [ ] Production Docker preparation
