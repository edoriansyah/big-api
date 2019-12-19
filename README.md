# Simple REST API

Create simple REST API using PHP Native

## Getting Started

Prerequisite please install [composer](http://getcomposer.org/) on your system.

Before we using this API, please run command below under `rest-api` directory

```
composer install
```

We now have a `/vendor` directory, and the [DotEnv](https://github.com/vlucas/phpdotenv) dependency is installed (we can also use our autoloader to load our classes from `/src` with no `include()` calls).

Create our local credentials in the .env file

`.env`

```
DB_HOST=localhost
DB_PORT=5432
DB_DATABASE=api_example
DB_USERNAME=api_user
DB_PASSWORD=api_password
```
