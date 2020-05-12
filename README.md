# Lumen + Mithril = Lumithril

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/shriker/lumen-mithriljs-starter/blob/master/LICENSE.md) [![Lumen](https://img.shields.io/badge/lumen-7.0-%23f4645f)](https://lumen.laravel.com/) [![Mithril](https://img.shields.io/badge/mithril-2.0.4-%231e5799)](https://mithril.js.org/)

A quick start project template with [Lumen](https://lumen.laravel.com/docs) and [Mithril](https://mithril.js.org/).

## Requirements

* PHP ^7.2.5, OpenSSL PHP Extension, PDO PHP Extension, Mbstring PHP Extension
* SSH (command-line) access to run [Composer](https://getcomposer.org/)
* [Node](https://nodejs.org/en/download/)

## Official Documentation

* Documentation for the Lumen framework can be found on the [Lumen website](https://lumen.laravel.com/docs).

* Documention for Mithril JavaScript framework may be found on the [Mithril website](https://mithril.js.org/).

## Installing

```bash
git clone https://github.com/shriker/lumen-mithril your-project
cd your-project
composer install
npm install
```

## Local PHP Server

Running the PHP backend
```bash
php -S localhost:8000 -t public
```

Watching the frontend with Webpack
```bash
npm run start
```

## Production Build

```bash
npm run build
```

## License

This open-sourced software is licensed under the [MIT license](https://opensource.org/licenses/MIT).
