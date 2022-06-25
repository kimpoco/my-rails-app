# README

### install & run server
$ docker-compose build
$ docker-compose run --rm app bundle install
$ docker-compose run --rm app bin/rails db:create db:migrate
$ docker-compose up
