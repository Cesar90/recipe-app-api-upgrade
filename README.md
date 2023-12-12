# recipe-app-api-upgrade

Project based on django rest framework with docker

# Build project with docker-compose

docker-compose build

# Run Linting

docker-compose run --rm app sh -c "flake8"

# Run Testing

docker-compose run --rm app sh -c "python manage.py test"
