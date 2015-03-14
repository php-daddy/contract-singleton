# Singleton Contract (Interface)

[![Build Status](https://travis-ci.org/php-daddy/contract-singleton.svg?branch=master)](https://travis-ci.org/php-daddy/contract-singleton)

## Installation

```bash
$ composer require "php-daddy/contract-singleton":"*"
```

## Usage

```php
<?php

use PhpDaddy\Contract\Singleton\AbstractSingleton;

class SingletonChild extends AbstractSingleton
{
}

$obj = new SingletonChild::getInstance();

```

See `example` directory, or by:

```php
<?php

use PhpDaddy\Contract\Singleton\Singleton;
use PhpDaddy\Contract\Singleton\SingletonTrait;

class SingletonStub implements Singleton
{
  use SingletonTrait;
}

$obj- new SingletonStub::getInstance();

```
