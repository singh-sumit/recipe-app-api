# recipe-app-api
Udemy TTD Django Recipe app

# To run linting
```sh
docker-compose run --rm <service_name> sh -c "flake8"
```

## To create `django project` inside container
```sh
docker-compose run --rm app sh -c "django-admin startproject app ."
```


## Start development server
```sh
docker-compose up
```
