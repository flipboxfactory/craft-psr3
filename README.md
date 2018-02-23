# PSR-3 Logger for Craft CMS
[![Join the chat at https://gitter.im/flipboxfactory/craft-psr3](https://badges.gitter.im/flipboxfactory/craft-psr3.svg)](https://gitter.im/flipboxfactory/craft-psr3?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Latest Version](https://img.shields.io/github/release/flipboxfactory/craft-psr3.svg?style=flat-square)](https://github.com/flipboxfactory/craft-psr3/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/flipboxfactory/craft-psr3/master.svg?style=flat-square)](https://travis-ci.org/flipboxfactory/craft-psr3)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/flipboxfactory/craft-psr3.svg?style=flat-square)](https://scrutinizer-ci.com/g/flipboxfactory/craft-psr3/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/flipboxfactory/craft-psr3.svg?style=flat-square)](https://scrutinizer-ci.com/g/flipboxfactory/craft-psr3)
[![Total Downloads](https://img.shields.io/packagist/dt/flipboxfactory/craft-psr3.svg?style=flat-square)](https://packagist.org/packages/flipboxfactory/craft-psr3)

This package provides simple mechanism for PSR-3 logging via Craft CMS.

## Installation

To install, use composer:

```
composer require flipboxfactory/craft-psr3
```

## Testing

``` bash
$ ./vendor/bin/phpunit
```

## Usage
Define it as a component in your plugin
```php 
'components' => [
    'psr3logger' => [
        'class' => flipbox\craft\psr3\Logger::class
     ]
]
```
or via your composer as an 'extra' definition
```json
"components": {
  "psr3logger": "flipbox\\craft\\psr3\\Logger"
}
```

## Contributing

Please see [CONTRIBUTING](https://github.com/flipboxfactory/craft-psr3/blob/master/CONTRIBUTING.md) for details.


## Credits

- [Flipbox Digital](https://github.com/flipbox)

## License

The MIT License (MIT). Please see [License File](https://github.com/flipboxfactory/craft-psr3/blob/master/LICENSE) for more information.
