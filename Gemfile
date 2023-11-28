source "https://rubygems.org"

# Programming language
# This MUST be identical to the version set in .ruby-version.
ruby "3.2.2"

# Framework
# This MUST be specified as an absolute version number to stop any other gems being able to alter the version used.
gem "rails", "7.1.2"

# Web server
gem "puma", ">= 5.0"

# Database
gem "pg", "~> 1.1"

# Caching
gem "redis", ">= 4.0.1"
gem "kredis"
gem "bootsnap", require: false

# Internationalization
# This MUST be specified as the same major version as the version of the Ruby on Rails framework.
gem "rails-i18n", "~> 7.0.0"

# API
gem "jbuilder"

# Assets
gem "sprockets-rails"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"

# UI
gem "view_component"

# Utilities
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Gems for development and test environments
group :development, :test do
  # Debugger
  gem "debug", platforms: %i[ mri windows ]
end

# Gems for development environment
group :development do
  # Console for exceptions pages
  gem "web-console"
end

# Gems for test environment
group :test do
  # System testing
  gem "capybara"
  gem "selenium-webdriver"
end
