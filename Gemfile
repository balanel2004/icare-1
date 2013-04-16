source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails', '4.0.0.beta1'

# Servers
gem 'thin'
gem 'unicorn'

# Multi-environment configuration
gem 'simpleconfig'

# API
gem 'rabl'

# ODM and related
gem 'client_side_validations', git: 'git://github.com/bcardarella/client_side_validations.git', branch: '4-0-beta'
gem 'client_side_validations-turbolinks'
gem 'kaminari'
gem 'mongoid', git: 'git://github.com/mongoid/mongoid.git'
gem 'mongoid_geospatial', git: 'git://github.com/nofxx/mongoid_geospatial.git'
gem 'mongoid_slug'
gem 'validates_timeliness'

# Geospatial data library
gem 'rgeo'

# Facebook integration
gem 'koala'
gem 'omniauth-facebook'

# Performance and Exception management
gem 'airbrake'
gem 'newrelic_rpm'
gem 'newrelic_moped'

# Security
gem 'secure_headers'

# Miscellanea
gem 'google-analytics-rails'
gem 'haml'
gem 'http_accept_language'
gem 'jquery-rails'
gem 'nokogiri'
gem 'resque', require: 'resque/server' # Resque web interface
gem 'rest-client'

group :development, :test do
  gem 'debugger'
  gem 'delorean'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry'
  gem 'pry-rails'
end

group :development do
  gem 'bullet'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :test do
  gem 'capybara'
  gem 'coveralls', require: false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
  gem 'mongoid-rspec'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webmock', require: false
end

group :assets do
  gem 'coffee-rails', '~> 4.0.0.beta1'
  gem 'compass-rails'
  gem 'haml_assets'
  gem 'handlebars_assets'
  gem 'i18n-js'
  gem 'jquery-turbolinks'
  gem 'less-rails'
  gem 'sass-rails', '~> 4.0.0.beta1'
  gem 'therubyracer'
  gem 'turbolinks'
  gem 'twitter-bootstrap-rails'
  gem 'uglifier'
end
