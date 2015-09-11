Strict mode PHP
===============

This is a tiny library that enables strict error checking in PHP;
i.e., it enables all errors (`E_ALL`) and throws an `ErrorException`
for every error. It uses Composer's autoload facility to always load.

Installation
------------

    composer require dsv-su/strict-mode-php '~1.0'

Usage
-----

```php
require 'vendor/autoload.php';
echo "$x\n"; // throws ErrorException
```
