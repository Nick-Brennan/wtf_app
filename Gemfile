source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
# Use sqlite3 as the database for Active Record
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.15'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'hirb'

gem 'devise'

gem "fog-aws"

gem 'figaro'

# Allows likes and votes
gem 'acts_as_votable', '~> 0.10.0'

# Google Maps gem
gem 'gmaps4rails'

gem 'underscore-rails'

gem 'geocoder'

# Helper to convert time to relative time
gem 'time_ago_in_words', '~> 0.1.1'

#pagination gem
gem 'will_paginate', '~> 3.1.0'

#adding bootstrap styling to paginate gem"
gem 'will_paginate-bootstrap'


gem 'bootstrap-sass', '~> 3.3.6'

#image uploading
gem 'carrierwave'

#image processing
gem 'mini_magick', '~> 4.5', '>= 4.5.1'


gem 'dotenv-rails', :groups => [:development, :test]


# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'factory_girl_rails'
  gem 'ffaker'
  gem 'rspec-rails'
  gem 'simplecov', require: false
  gem 'spring'
  gem 'shoulda-matchers', '~> 3.1'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
  gem 'rails_12factor'
end
