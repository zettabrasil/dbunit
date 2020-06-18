
This is a fork of [PHPUnit](https://github.com/sebastianbergmann/dbunit) to use with phpunit 8 and 9
The original is no longer maintained

# DbUnit

[PHPUnit](https://phpunit.de/) extension for database interaction testing.

## Installation

### Composer

If you use [Composer](https://getcomposer.org/) to manage the dependencies of your project then you can add DbUnit as a development-time dependency to your project:

```
$ composer require --dev phpunit/dbunit
```

### PHP Archive (PHAR)

You can download a PHAR of DbUnit:

```
$ wget https://phar.phpunit.de/dbunit.phar
```

The example below shows how to configure PHPUnit to load all `*.phar` files found in a given directory (`tools/phpunit.d` in this example):

```xml
<?xml version="1.0" encoding="UTF-8"?>
<phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:noNamespaceSchemaLocation="https://schema.phpunit.de/6.0/phpunit.xsd"
         extensionsDirectory="tools/phpunit.d">
</phpunit>
```
