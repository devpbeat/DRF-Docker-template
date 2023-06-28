# DRF-Docker-template
Template for Django REST Framework projects dockerized for all environments.


## Local Development

### Requirements
- Docker
- Docker Compose

### Setup
1. Clone the repository
2. Run `docker compose build`
2. Run `docker compose up -d`
3. Run `docker compose exec template-web python manage.py migrate --noinput`
4. Run `docker compose exec template-web python manage.py createsuperuser`
5. Run `docker compose exec template-web python manage.py collectstatic --no-input --clear`


## Staging

In development

## Production

In development
