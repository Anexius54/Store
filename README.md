# Clothing store

[![Unit Tests & Lint](https://github.com/Anexius54/Store/actions/workflows/main.yml/badge.svg)](https://github.com/Anexius54/Store/actions/workflows/main.yml)

This is the clothing store with the ability to add and remove items

### Ruby version
 * 3.0.2
### PostgreSQL installation
 * sudo apt install postgresql
 * sudo gem install pg
 * sudo -u postgres psql -c "ALTER USER postgres PASSWORD 'postgres';"
### Gems and database setup
 * gem install bundler
 * bundle install
 * rails db:create
 * rails db:migrate
### Run
 * bin/rails s
