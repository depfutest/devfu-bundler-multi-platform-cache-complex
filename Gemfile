source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '~> 3.0.0'

gem 'rails', '~> 7.0'

gem 'reline', '~> 0.2.2'

gem 'dalli'

# Translation (locale) files for rails-related I18n keys
# gem 'rails-i18n', '>= 6.0.0'

# Use Puma as the app server (for development)
gem 'puma', '~> 5.0'

gem 'pg', '~> 1.2'

# monitoring / error tracking
gem 'newrelic_rpm'
gem 'sentry-rails'
gem 'sentry-ruby'

# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 6.0.rc'

gem 'dotenv-rails', '~> 2.7'

# For all HTTP needs
gem 'http'

gem 'audited', '~> 5.0'

gem 'rack-attack'

# We use advisory locking for availability reservations
gem 'pg_lock'

# We use Cloudflare, and this takes care of correctly detecting the client IP using the CF-Connecting-IP header
gem 'cloudflare-rails'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'guard-rspec', require: false
  gem 'rspec_junit_formatter'
  gem 'rspec-rails', '~> 5.0'

  gem 'simplecov', require: false
  gem 'simplecov-cobertura', require: false
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'rubocop', '~> 1.0', require: false
  gem 'rubocop-rails', '~> 2.0', require: false
  gem 'web-console', '~> 4.1'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'factory_bot_rails'
  gem 'pry-byebug'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'

  gem 'webmock'
end

gem 'validates_email_format_of', '~> 1.6'
