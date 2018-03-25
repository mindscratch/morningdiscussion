# morning discussion

A place to have discussions, in the morning.


## Get Started

The site uses [Known](https://github.com/idno/known) and is run using Docker and Docker Compose.

Clone [known](https://github.com/mindscratch/known) which uses Docker Compose to setup Known with MySQL and Nginx.

Create a file named `env` in the directory where `known` was cloned into. The contents should be similar the those
below with values you'd like to use:

```
MYSQL_ROOT_PASSWORD=mysqlrootpassword
KNOWN_DB_PASSWORD=knowndbpassword
KNOWN_DB_NAME=knowndbname
KNOWN_DB_USER=knowndbuser
```

Then, `docker-compose up` and you're ready to go.
