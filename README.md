# Matomo + MariaDB containers

Matomo (Piwik) analytics dockerized with MariaDB.

Create a `matomo.env` file with the following database credenitals:

```
MYSQL_ROOT_PASSWORD=your_root_passowrd
MYSQL_DATABASE=your_db_name
MYSQL_USER=your_db_user_name
MYSQL_PASSWORD=your_db_password
```

Then start the services with `docker-compose up`

More details on my blog, including [setting geolocation data and deploying the Matomo container](https://danielwachtel.com/devops/dockerizing-a-matomo-web-analytics-app).
