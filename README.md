# README

  rails new docker_on_rails --database=postgresql
  docker-compose run rails /bin/bash
  bundle exec rails webpacker:install
  yarn
  bundle
  bundle exec rails db:create db:migrate

  docker-compose up
  docker-compose down

  bundle exec rails g scaffold post title:string body:text published:boolean
  bundle exec rails db:migrate

  bundle exec rails dev:cache
