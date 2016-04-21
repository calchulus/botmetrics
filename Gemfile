source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5.1'
# Use postgresql as the database for Active Record
gem 'pg',    '~> 0.18.2'
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks',    '~> 2.5.3'

gem 'haml',                     '~> 4.0.6'
gem 'bootstrap-sass',           '~> 3.3.1'
gem 'sass-rails',               '~> 5.0.1'
gem 'autoprefixer-rails',       '~> 6.3.3'
gem 'jquery-rails',             '~> 4.0.3'
gem 'coffee-rails',             '~> 4.1.0'
gem 'jquery-ui-rails',          '~> 5.0.3'
gem 'simple_form',              '~> 3.1.0'
gem 'modernizr-rails',          '~> 2.7.1'

# Auth
gem 'devise',                  '~> 3.4.1'

# Mixpanel
gem 'mixpanel-ruby',          '~> 2.2.0', require: 'mixpanel-ruby'
# Redis
gem 'relax-rb',               github: 'zerobotlabs/relax-rb', ref: 'typing', require: 'relax'
gem 'sidekiq',                    '~> 4.1.0'
gem 'sinatra',                    '~> 1.4.6'
gem 'redis-namespace',            '~> 1.5.2'

gem 'passenger',                '~> 5.0.27'

group :development do
  # Foreman to launch processes
  gem 'foreman',     '~> 0.70.0'
end

group :development, :test do
  gem 'rspec-rails',              '~> 3.4.2'
  gem 'rspec-its',                '~> 1.2.0'
  gem 'byebug',                   '~> 2.0.0'
  gem 'timecop',                  '~> 0.7.4'
end

group :test do
  gem 'database_cleaner',         '~> 1.3.0'
  gem 'factory_girl_rails',       '~> 4.5.0'
  gem 'shoulda-matchers',         '~> 2.7.0'
  gem 'webmock',                  '~> 1.22.3'
  gem 'stripe-ruby-mock',         '~> 2.2.1', require: 'stripe_mock'
end

group :production do
  gem 'rails_12factor',           '~> 0.0.3'
  gem 'newrelic_rpm',             '~> 3.9.9'
  gem 'bugsnag',                  '~> 2.8.13'
  gem 'lograge',                  '~> 0.3.6'
end

group :assets do
  gem 'uglifier',                 '~> 2.7.1'
end
