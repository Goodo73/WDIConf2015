source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use postgresql as the database for Active Record
gem 'pg'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# code climate static code quality analysis. This allows test coverage %
# gem 'codeclimate-test-reporter', group: :test

# CarrierWave for file uploads
gem 'carrierwave'

group :development, :test do
  # Required by Windows devs
  # allows time zone data to be accessed on windows
  gem 'tzinfo-data'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # development gems recommended by Matt Swan
  gem 'pry-rails'
  gem 'better_errors'
  gem 'meta_request'
  gem 'binding_of_caller'
  gem 'annotate'
  gem 'dotenv-rails'
  gem 'rspec-rails'
end

group :production do
  # gem below required for Heroku deployment
  gem 'rails_12factor'
  gem 'cloudinary'
end

