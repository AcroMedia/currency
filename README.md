Currency
========

This is forked from commercie/currency, which has diverged from bartfeenstra/currency. This is the version required by [Currency](https://drupal.org/project/currency) if you're using [Composer Manager](https://drupal.org/project/composer_manager) instead of the module's built-in autoloader and vendor dir.

# Introduction
A language-independent library that provides metadata for current and historic
currencies:
* ISO 4217 currency codes and numbers
* Currency signs
* The number of decimals a currency has
* Where (ISO 3166 country codes) and when (ISO 8601 dates) currencies were and
  are used
* Fixed exchange rates (usually historic)

# Usage
* Currency information is stored in YAML files in `/resources`.
* PHP helpers:
  * `\AcroMedia\Currency\Currency` is a basic class that serves as a container and a controller for
working with the YAML resources.
  * `\AcroMedia\Curency\Input` contains a parser for user input.

# Requirements
The library does not have any global requirements.

## Testing
* PHPUnit 3.7.*

## Resources
* Any YAML parser.

## PHP
* PHP 5.3.x or higher
* Symfony YAML 2.1.*

# Integrates with
* [Composer](http://getcomposer.org) (as
[acromedia/currency](https://packagist.org/packages/acromedia/currency))
* [Drupal](https://drupal.org) (through [Currency](https://drupal.org/project/currency))
