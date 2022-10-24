# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'rails', '~> 7.0.4'

# BASE
gem 'bootsnap', require: false
gem 'devise'
gem 'draper'
gem 'pg'
gem 'puma'
gem 'rails_event_store'
gem 'sidekiq'
gem 'sprockets-rails'

# FRONT
gem 'cssbundling-rails'
gem 'jsbundling-rails'
gem 'slim-rails'
gem 'stimulus-rails'
gem 'turbo-rails'

group :development, :test do
  gem 'awesome_print'
  gem 'benchmark-ips'
  gem 'byebug'
  gem 'capybara'
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'pry-byebug'
  gem 'pry-rescue'
  gem 'pry-stack_explorer'
  gem 'rspec-rails'
  gem 'webdrivers'
end

group :development do
  gem 'annotate'
  gem 'letter_opener'
  gem 'listen'
  gem 'reek'
  gem 'rubocop',             require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails',       require: false
  gem 'rubocop-rake',        require: false
  gem 'rubocop-rspec',       require: false
  gem "rubycritic",          require: false
  gem 'spring'
  gem 'web-console'
end

group :test do
  gem 'database_cleaner'
  gem 'ruby_event_store-rspec'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'timecop'
end
