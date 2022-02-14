# php-validated-properties-phpstan
PHPStan extension for the php-validated-properties package

To let PHPStan understand the ```prinsfrank/php-validated-properties``` package and to enable it to prevent any errors that can be detected using static analysis, a PHPStan plugin is provided. To add it to your phpstan.neon, simply run the command below;

```
composer require prinsfrank/php-validated-properties-phpstan
```

And add the following line to your includes section in your phpstan.neon file:

```neon
includes:
    - vendor/prinsfrank/php-validated-properties/development/PHPStan/extension.neon
```
