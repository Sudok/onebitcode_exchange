# Gw-exchange!

A simple app for currency conversions.

### Tech:
  - Ruby 2.3
  - Rails 5.0.2
  - Coffeescript

### Test:

  - Rspec(backend).
  - Capybara(front-end).

### Dependencies:

* [Fixer.io] - Api for currency conversion.

### How to install:

```sh
$ docker-compose build
$ docker-compose run --rm website rake db:create db:migrate
$ docker-compose up
```
