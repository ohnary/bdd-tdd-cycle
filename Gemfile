source 'https://rubygems.org'

ruby '2.2.3'
gem 'rails', '4.2.1'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
  gem 'pg'
group :development, :test do
#  gem 'debugger'
  gem 'byebug'
  gem 'launchy'
  gem 'rspec-rails'
  gem 'simplecov'
  gem 'test-unit', '= 2.5.5'
  gem 'activeresource' 
end
group :test do
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'
  gem 'database_cleaner'
  gem 'capybara'
end 
group :production do
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'therubyracer'
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
gem 'haml-rails'
