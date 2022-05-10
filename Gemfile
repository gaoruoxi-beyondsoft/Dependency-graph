source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.3'
# Use Puma as the app server
gem 'puma'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

gem 'aruba', '0.14.11'
gem 'aws-sdk-ec2', '~> 1'
gem 'bcrypt_pbkdf'
gem 'capybara', '~> 3.0'
gem 'capybara-mechanize'
gem 'chatops-controller', '~>3.0'
gem 'chatterbox-client'
gem 'colorize'
gem 'cuprite'
gem 'dropybara'
gem 'ed25519'
gem 'failbot', '2.0.1'
gem 'failbot_rails', '0.5.0'
gem 'faraday', '0.17.3'
gem 'json'
gem 'net-ping'
gem 'net-scp'
gem 'netrc'
gem 'octokit', '~> 4.21'
gem 'posix-spawn'
gem 'resque'
gem 'rest-client'
gem 'rotp'
gem 'rspec'
gem 'semverly'

# Source qaboot from GPR
source 'https://rubygems.pkg.github.com/github' do
  gem 'qaboot'
end

group :developemnt do
  gem 'pry'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  # gem 'spring'
  # gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'pry-coolline'
end

group :test do
  # # Adds support for Capybara system testing and selenium driver
  # gem 'capybara', '>= 2.15'
  # gem 'selenium-webdriver'
  # # Easy installation and use of chromedriver to run system tests with Chrome
  # gem 'chromedriver-helper'
  gem 'mocha'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
