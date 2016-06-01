source 'https://rubygems.org'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Bootstrap (http://getbootstrap.com)
gem 'bootstrap-sass', '~> 3.3.5'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# Solves the problems of setting project-specific environment vars
gem 'dotenv-rails'
# Use for scalable fonts
gem "font-awesome-rails"
# Makes http fun again
gem 'httparty'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# Use postgresql as the database for Active Record
gem 'pg'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
# Enables you to use fake people, places, or things (e.g. addresses)
gem 'faker'
# Paginate pages
gem 'will_paginate', '~> 3.1.0'

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

group :test do
  # A library for setting up Ruby objects as test data. (https://github.com/thoughtbot/factory_girl)
  gem 'database_cleaner'
  # Headless driver for capybara testing based on PhantomJS
  gem 'poltergeist'
end

group :development, :test do
  # Acceptance test framework for web applications. (https://github.com/jnicklas/capybara)
  gem 'capybara'
  # Ensures a clean state during tests
  gem 'factory_girl'
  # Saves and opens a page for when debugging tests
  gem 'launchy'
  # Call 'binding.pry' anywhere in the code to stop execution and get a debugger console
  gem 'pry-rails'
  # Rspec is used for Bheavior Driven Development (http://rspec.info, https://github.com/rspec/rspec)
  gem 'rspec-rails', '~> 3.0'
  # Aids in unit testing relationships (https://github.com/thoughtbot/shoulda-matchers)
  gem 'shoulda-matchers', '~> 3.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  # # Access an IRB console on exception pages or by using <%= console %> in views
  # gem 'web-console', '~> 2.0'
end

group :production do
  gem 'puma', '2.11.1'
  gem 'rails_12factor', '0.0.2'
end

ruby '2.0.0'
