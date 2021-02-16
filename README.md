# ranking_media

## languages and frameworks
- Ruby on rails
- Vue.js

## versions
### Ruby 

ruby 2.6.5p114 (2019-10-01 revision 67812) [x86_64-darwin19]

### Vue

@vue/cli 4.5.11


## setup
install ruby(ver 2.6 or later is recommended)

$ brew install ruby

$ ruby -v

ruby 2.6.5p114 (2019-10-01 revision 67812) [x86_64-darwin19]

## install bundler
$ bundle init

Gemfileでgem "rails"のコメントアウト外す

```
# frozen_string_literal: true
source "https://rubygems.o

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "rails"

```
$ bundle install --path vendor/bundle

$ bundle exec rails new . -B -d mysql --skip-turbolinks --skip-test

$ bundle

## yarn setup
$ brew install yarn

$ yarn install

$ rails webpacker:install

## create and migrate db

$ bundle exec rails db:create

$ bundle exec rails db:migrate

### clone this repositry

$ git clone https://github.com/3dstylee/spacely_web.git

## run rails

$ bundle exec rails s

