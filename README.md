# PHP OpenID Connect Basic Client for MISP OIDC Plugin

[![Latest Stable Version](http://poser.pugx.org/certmichelin/openid-connect-php/v)](https://packagist.org/packages/certmichelin/openid-connect-php) [![Latest Unstable Version](http://poser.pugx.org/certmichelin/openid-connect-php/v/unstable)](https://packagist.org/packages/certmichelin/openid-connect-php) [![PHP Version Require](http://poser.pugx.org/certmichelin/openid-connect-php/require/php)](https://packagist.org/packages/certmichelin/openid-connect-php)

A lightweight library used by MISP to enable user authentication through the OpenID Connect protocol.
It provides a simple and reliable implementation of the OpenID Connect flow, allowing MISP to integrate OpenID-based authentication without requiring in-depth knowledge of the protocol.

**This is a fork of [JakubOnderka/OpenID-Connect-PHP](https://github.com/JakubOnderka/OpenID-Connect-PHP)**

## Requirements

 1. PHP 8.0 or greater
 2. CURL extension
 3. JSON extension
 4. APCu for caching (optional)

## Install

1. Install library using composer.

```bash
composer require certmichelin/openid-connect-php
```

2. Include composer autoloader

```php
require __DIR__ . '/vendor/autoload.php';
```

