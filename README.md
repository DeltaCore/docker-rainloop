## Version: [1.12.0](http://www.rainloop.net/changelog/)

## Quickstart

To Start the container use the following command.

```
docker run -d -p "80:80" deltacore/rainloop
```

**or**

```
docker-compose up
```

use [docker-compose](https://github.com/docker/compose) .

## Save the Rainloop data persistent
If you want the Rainloop data persistent than use the exposed Volume with a command like this:
```
docker run -d -p "80:80" -v $(pwd)/data:/var/www/rainloop/data deltacore/rainloop
```

## Rainloop Specifica

### Contacts
This container supports all Database PHP extensions for the contacts:
- MySQL
- PostgreSQL
- SQLite


# LICENSE
The MIT License (MIT)

Copyright (c) 2016 Niclas Mietz
