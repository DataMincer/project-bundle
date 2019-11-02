# Composer default template for DataMincer bundle project

This project template provides a starter kit for managing your project
dependencies with [Composer](https://getcomposer.org/).

This repository contains the base set of packages pre-installed:

* [datamincer/core](https://bitbucket.org/datamincer/core/src/master/)
* [datamincer/plugins](https://bitbucket.org/datamincer/plugins/src/master/)
* [datamincer/launcher](https://bitbucket.org/datamincer/launcher/src/master/)

## Usage

First you need to [install composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

> Note: The instructions below refer to the [global composer installation](https://getcomposer.org/doc/00-intro.md#globally).
You might need to replace `composer` with `php composer.phar` (or similar) 
for your setup.

After that you can create the project:

```
$ composer create-project datamincer/project-bundle bundle-foobar --no-interaction --repository https://datamincer.bitbucket.io --stability dev
$ cd bundle-foo
```

With `composer require ...` you can download new dependencies to your 
installation. For instance, to install `crowdanki` plugins: 

```
$ composer require datamincer/crowdanki
```

The only function of this template ded is to provide default `composer.json` with configured DataMincer repository.


