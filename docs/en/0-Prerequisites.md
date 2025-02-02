[← Home](../../README-EN.md) | Prerequisites[(中文)](../zh/0-Prerequisites.md) | [Installation →](1-Installation.md)
***

# Requirements and Recommendations
Before using the Alibaba Cloud Client for PHP, please ensure your environment supports the following requirements and recommendations.


## Requirements
- You must use PHP 5.5.0 or later.
- if you use the `RsaKeyPair` (Only Japan station is supported) client, you will also need [OpenSSL PHP extension][OpenSSL]. 

## Recommendations
- Use [Composer][composer] and optimize automatic loading `composer dump-autoload --optimize`
- Install [cURL][cURL] 7.16.2 or later version
- Use [OPCache][OPCache]
- In a production environment, do not use [Xdebug][xdebug]

***
[← Home](../../README-EN.md) | Prerequisites[(中文)](../zh/0-Prerequisites.md) | [Installation →](1-Installation.md)

[composer]: https://getcomposer.org
[cURL]: http://php.net/manual/en/book.curl.php
[OPCache]: http://php.net/manual/en/book.opcache.php
[xdebug]: http://xdebug.org
[OpenSSL]: http://php.net/manual/en/book.openssl.php
