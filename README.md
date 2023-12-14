# recipe-app-api-upgrade

Project based on django rest framework with docker

# Build project with docker-compose

docker-compose build

# Create django project

docker-compose run --rm app sh -c "django-admin startproject app ."

# Run Linting

docker-compose run --rm app sh -c "flake8"

# Run Testing

docker-compose run --rm app sh -c "python manage.py test"

# Create core app

docker-compose run --rm app sh -c "python manage.py startapp core"
