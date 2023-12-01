# Changelog

## 1.2.0 / 2021-10-31

* Add a branch alias for 1.0.x
* Enable a PHP 8 compatible version of TwigCS to be installed
* Exclude "\Drupal\Core\Render\Element\Checkboxes" class of PHPMD StaticAccess rule (#17)
* Exclude "\Drupal\Component\Plugin\Factory\DefaultFactory" static access
* Exclude "\Drupal\Core\Site\Settings" static access
* Add common ignores to PHPCS
* Modify readme file to change syntax for copying all dist files
* Explicitly set twigcs ruleset
* Exclude MissingImport from cleancode rules

## 1.1.0 / 2020-11-06

* Allow more versions of phpcpd to be installed
* Allow twigcs 4.0 to be used
* Remove composer from require-dev
* Fixes #6. Use GrumPHP stable version release
* Merge pull request #5 from mohit-rocks/master
* Adding support for twigcs so it gets automatically downloaded

## 1.0.0 / 2020-07-12

* Replace abandoned package with replacement
* Add video of upgrade to README

## 1.0.0-beta9 / 2020-06-10

* Update README for changes from GrumPHP 0.19
* Introduce smaller versions of ASCII art
* Move to grumphp-shim's latest version (**breaking release**, read documentation)

## 1.0.0-beta8 / 2020-06-10

* Update phpcs.xml.dist with one matching Drupal core

## 1.0.0-beta7 / 2020-04-24

* Move composer to require-dev

## 1.0.0-beta6 / 2020-04-21

* Use the scaffold plugin to copy files
* Upgrade to GrumPHP 0.18
