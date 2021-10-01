# Hello World Package for PHP Composer #

This is a hello world package for php composer. Training-composer

## Usage ##

```bash
$ composer require joko-icube/hello-world

$ nano test.php
```

```php
<?php
require_once "vendor/autoload.php";

$hello = new Joko\Demo\Hello();
echo $hello->hello();

echo "\n";
```

```bash
$ php test.php
```

It will print `Hello World !!!!!`.