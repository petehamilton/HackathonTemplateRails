source 'https://rubygems.org'

gem 'rails', '3.2.1'



# Twitter Bootstrapping
gem 'twitter-bootstrap-rails'

# Pagination
gem 'will_paginate'
gem 'bootstrap-will_paginate'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'haml-rails'
gem 'simple_form'       # Nice forms
gem 'rufus-scheduler'   # Task Scheduling

group :development do
  gem 'rails3-generators' # for factory_girl_rails and simple_form
  gem 'heroku'            # Useful for deploying for demos
  gem 'sqlite3'           # Local development
end

group :production do
  gem 'pg' # Required by postgres
end

group :test, :development do
  gem "rspec-rails"
  gem 'rspec-instafail'
  gem 'rb-fsevent'
  gem 'growl'
  gem 'pry'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem "factory_girl_rails"
  gem "capybara"
  gem 'guard-spork'
  gem "guard-bundler"
  gem "guard-rspec"
  gem "guard-migrate"
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
