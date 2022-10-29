This repo is to allow static analysis for the braintree library with phpstan

The phpdoc was mostly taken from an older version of the repo when braintree supported the native docs.

# Installing
## Automatic
Using composer and allowing plugins will allow this to be a single command install

```
composer require sykescottages/phpstan-braintree
```

## Manual
Add in the rules file manually by adding the following to your neon file

```neon
includes:
	- vendor/sykescottages/phpstan-braintree/rules.neon
```