This repository is already deprecated. Use [ttskch/symfony-micro-skeleton](https://github.com/ttskch/symfony-micro-skeleton) instead.

---

# ttskch/Silex-Skeleton

Forked from [silexphp/Silex-Skeleton](https://github.com/silexphp/Silex-Skeleton) and added folowing features.

- bootstrap4 based templates
- bootstrap4 based form themes
- translation support
- scss support (via gulp)

## Requirements

- PHP 5.4+
- npm

## Installation

```bash
$ git clone git@github.com:ttskch/Silex-Skeleton.git
$ cd Silex-Skeleton
$ composer install
```

## Usage

```bash
$ COMPOSER_PROCESS_TIMEOUT=0 composer run
```

Then, browse to http://localhost:8888/index_dev.php/

## Building scss

```bash
$ npm run build   # build just once
```

```bash
$ npm run watch   # watch web/scss/*.scss and build automatically
```
