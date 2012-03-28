Prototypr aim to provide a pseudo application frame for the Symfony2 framework.

## Installation

### Install vendors

``` bash
$ bin/vendors install
```

### Create the database

The default database name is 'prototypr'.

``` bash
$ app/console doctrine:database:create
```

### Create the schema

``` bash
$ app/console doctrine:schema:create --force
```

### Load the fixtures

``` bash
$ app/console doctrine:fixtures:load
```

### Clear the cache

This will rebuild the routing cache

``` bash
$ app/console cache:clear
```
