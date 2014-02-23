source 'https://rubygems.org'

ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Use postgresql for database
gem 'pg'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

group :assets do
  # Enable asset pipeline
  gem 'sprockets-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  # Use Uglifier as compressor for JavaScript assets
  gem 'uglifier', '>= 1.3.0'

  # Use this for CSS compression
  gem 'yui-compressor'

  # Use CoffeeScript for .js.coffee assets and views
  gem 'coffee-rails', '~> 4.0.0'
end

group :development, :test do
  # RSpec for testing
  gem 'rspec-rails', '~> 3.0.0.beta'

  # DSD: why do I need this? shouldn't rspec-rails call this?
  # DSD: Update when I have internet!!
  gem 'rspec-collection_matchers', '0.0.2'

  gem 'capybara'

  gem 'spring'
  gem 'spring-commands-rspec'

  # DSD: Update when I have internet!!
  gem 'factory_girl_rails', '4.3.0'
end

# HAML for html
gem 'haml'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

gem 'rails_12factor', group: :production

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
