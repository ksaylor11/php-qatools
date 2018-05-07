# php-qatools
Collection of PHP QA tools

## PHP_CodeSniffer

[documentation](https://github.com/squizlabs/PHP_CodeSniffer)

Install:

`composer global require "squizlabs/php_codesniffer=*"`

Usage:

For `phpcs`

Integrate with Jetbrains [see documentation](https://confluence.jetbrains.com/display/PhpStorm/PHP+Code+Sniffer+in+PhpStorm)

Use custom configuration file: [phpcs.xml.dist](php.xml.dist) *thanks to Woody Gilk http://shadowhand.me/configuring-php-style-checks-with-composer/*

For `phpcbf`

`phpcbf <file or directory>`

## PHPMD

[documentation](https://phpmd.org/)

Install:

`composer global require "phpmd/phpmd=*"`

Usage:

Integrate with Jetbrains [see documentation](https://www.jetbrains.com/help/idea/using-php-mess-detector.html#d826777e13)


## PHPUnit

[documentation](https://phpunit.readthedocs.io/en/7.1/)

Install:

`composer global require "phpunit/phpunit=*"`

## PHP Coding Standards Fixer

[documentation](https://cs.sensiolabs.org/)

Install

`composer require "friendsofphp/php-cs-fixer"`

Usage:

Use custom configuration file: [.php_cs](.php_cs). This configuration will check against PSR1 and PSR2 coding conventions as well as clean up unused imports. (Similar to the code cleanup options that Jetbrains provides)
