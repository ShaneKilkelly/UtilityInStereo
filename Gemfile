source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'bootstrap-sass'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.0.1'
gem 'will_paginate', '3.0.3'
gem 'newrelic_rpm'
gem 'foreman'
gem 'unicorn'
gem 'pry'

gem "jquery-rails", "~> 2.1.3"
gem 'jquery-ui-rails'

gem 'event-calendar', :require => 'event_calendar'

group :development do
  gem 'sqlite3', '1.3.5'
  gem 'annotate', '~> 2.4.1.beta'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

group :test, :development do
  gem 'rspec-rails', '2.9.0'
  gem 'rb-fsevent'
  gem 'thin'
  gem 'guard-rspec', '0.5.5'
  gem 'guard-spork', '0.3.2'
  gem 'spork', '0.9.0'
  gem 'fuubar'
end

group :test do
  gem 'capybara', '1.1.2'
  gem 'factory_girl_rails', '1.4.0'
  gem 'cucumber-rails', '1.2.1', require: false
  gem 'database_cleaner', '0.7.0'
end

group :production do
  gem 'pg', '0.12.2'
end