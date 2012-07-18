source 'https://rubygems.org'

gem 'rails'
gem 'haml-rails'
gem 'jquery-rails'
gem 'puma'
gem 'sorcery'
gem 'delayed_job_active_record'
gem 'gettext_i18n_rails'
gem 'roadie'
gem 'cancan'
gem 'public_activity'
gem 'pusher', :require => false # Do not require since we do not use it
gem 'friendly_id'

group :production do
  gem 'pg'
end

group :development do
  gem 'sqlite3'
  gem 'yard'
  gem 'rails_best_practices', :require => false
  gem 'gettext', :require => false
  gem 'ruby_parser', :require => false
end

group :assets do
  gem 'uglifier'
  gem 'therubyracer'
  gem 'sass-rails'
  gem 'compass-rails'
  gem 'zurb-foundation', '~> 3.0.1'
end

group :development, :test do
  gem 'ffaker'
  gem 'fabrication'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'rspec-rails'
  gem 'letter_opener'
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'simplecov', :require => false
end
