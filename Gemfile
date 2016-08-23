source "https://rubygems.org"

gem "rails", "~> 4.2", ">= 4.2.7.1"

gem 'turbolinks',   '2.3.0'
gem 'jbuilder',     '2.2.3'
gem 'sdoc',         '0.4.0', group: :doc

# Authentication
gem "devise"
gem "omniauth-facebook"

# Authorization
gem "cancancan"

# Layout
gem "bootstrap-sass"
gem "bourbon"

# Common
gem "sass-rails", "~> 5.0.4"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.1.0"
gem "jquery-rails"
gem "kaminari"
gem "draper"

# ORM
gem "mysql2", "0.3.21"
gem "ar-octopus"

# Redis
gem "redis-rails"

# Search
gem "searchkick"
gem "ransack"

# Mail sending
gem "mandrill-api"
gem "gibbon"

# Support
gem "dotenv-rails"
gem "config"
gem "carrierwave-aws"
gem "faraday_middleware-aws-signers-v4",
  git: "https://github.com/framgia/faraday_middleware-aws-signers-v4.git"
gem "rubyXL", "~> 3.3", ">= 3.3.21"

# Read Spreadsheets
gem "roo", "~> 2.4.0"

# Deployment
gem "unicorn"
gem "unicorn-worker-killer"
gem "capistrano-rails"
gem "capistrano-rvm"
gem "capistrano-sidekiq"
gem "capistrano-bundler"
gem "capistrano3-unicorn"
gem "aws-sdk", "~> 2.3.9"
gem "simple_form"
gem "ckeditor"
gem "mini_magick"
gem "sidekiq"

# Data Migration Tool
gem "tiny_tds"

# Soft delete
gem "paranoia", "~> 2.0"
gem "deep_cloneable", "~> 2.2.1"

group :development, :test, :staging, :staging_framgia do
  gem "pry-rails"
  gem "pry-byebug"
  gem "better_errors"
  gem "rack-mini-profiler", require: false
  gem "shoulda-matchers"
  gem "faker"
end

group :test do
  gem "rspec-rails", "~> 3.3.3"
  gem "rspec-collection_matchers"
  gem "factory_girl_rails"
  gem "simplecov"
  gem "simplecov-rcov"
end

group :development, :test do
  gem 'sqlite3',     '1.3.9'
  gem 'byebug',      '3.4.0'
  gem 'web-console', '2.0.0.beta3'
  gem 'spring',      '1.1.3'
end

group :production do
  gem 'pg',             '0.17.1'
  gem 'rails_12factor', '0.0.2'
end

group :development do
  gem "rubocop", "~> 0.40.0", require: false
  gem "foreman"
  gem "rubocop-checkstyle_formatter"
  gem "brakeman"
  gem "reek"
  gem "bundler-audit", "~> 0.4.0"
  gem "rails_best_practices"
  gem "bullet"
end

gem "rails_admin"