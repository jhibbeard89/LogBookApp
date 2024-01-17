source "https://rubygems.org"

ruby "3.2.2"

###########################
# Rails and Dependencies #
###########################
gem "rails", "~> 7.1.2"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[windows jruby mingw mswin x64_mingw]
gem "bootsnap", require: false

###################
# Authentication  #
###################

gem "devise"

################
# Front-end CSS #
################
gem "tailwindcss-rails"

####################
# Form and UI      #
####################

# Empty for now

#################
# Security Tools #
#################

# Empty for now

####################
# Data Management  #
####################

# Empty for now

####################
# Background Jobs  #
####################

gem "redis", ">= 4.0.1"

###############
# Development #
###############
group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'bullet'
  gem 'rubocop'
  gem 'rubocop-rails'
  gem 'rubocop-rake'
  gem 'rubocop-performance', '~> 1.18'
  gem "web-console"
  gem 'mailtrap'
end

###############
# Testing     #
###############
group :test do
  gem "capybara"
  gem 'simplecov', '~> 0.22.0', require: false
  gem 'factory_bot_rails'
  gem 'rails-controller-testing'
  gem 'rspec-rails', '~> 6.0.0'
  gem "rubocop-rspec"
  gem "rubocop-capybara"
  gem "selenium-webdriver", "~> 4.0"
  gem 'shoulda-matchers', '~> 5.0' # provides RSpec one-liners to test common Rails functionality
  gem 'warden'
  gem 'warden-rspec-rails'
  gem "webdrivers"
  # test
end
