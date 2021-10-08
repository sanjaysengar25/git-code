# Develop REST API with Lumen and JWT authentication

# Installation

1. Clone this repo

```
https://github.com/sanjaysengar25/git-code.git
```

2. Install composer packages

```
cd lumen-rest-api-jwt-auth
$ composer install
```

3. Create and setup .env file

```
make a copy of .env.example
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
$ php artisan jwt:secret
```

4. Migrate and insert records

```
$ php artisan migrate
```

