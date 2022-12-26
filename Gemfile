source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.3"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "bootsnap", require: false
gem "image_processing", "~> 1.2"
gem 'ransack', '~> 3.2', '>= 3.2.1'
gem 'will_paginate', '~> 3.1'
gem 'figaro'
gem 'friendly_id', '~> 5.4.0'
gem 'devise', '~> 4.8', '>= 4.8.1'


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data"
gem 'tzinfo'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
