# PSUSphere

## How to Run with Docker

1. Install Docker Desktop from docker.com
2. Go to the `for_client` folder
3. Open a terminal there and run:
   docker-compose up
4. Open http://localhost:8000 in your browser

## First time only — create admin account
docker-compose exec web python manage.py createsuperuser