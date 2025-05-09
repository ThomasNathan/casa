# frozen_string_literal: true

source "https://rubygems.org"

ruby "3.1.3"
gem "rails", "~> 7.0.4"

gem "after_party" # post-deployment tasks
gem "amazing_print" # easier console reading
gem "azure-storage-blob", require: false
gem "bugsnag" # tracking errors in prod
gem "caxlsx", "~> 3.3" # excel spreadsheets - TODO can we remove this version restriction?
gem "caxlsx_rails", "~> 0.6.3" # excel spreadsheets - TODO can we remove this version restriction?
gem "cssbundling-rails", "~> 1.1" # compiles css
gem "delayed_job_active_record"
gem "devise" # for authentication
gem "devise_invitable"
gem "httparty" # for making HTTP network requests 🥳
gem "twilio-ruby" # twilio helper functions
gem "draper" # adds decorators for cleaner presentation logic
gem "faker" # creates realistic seed data, valuable for staging and demos
gem "filterrific" # filtering and sorting of models
gem "friendly_id", "~> 5.5.0" # allows us to use a slug instead of casa case ids in their URLs
gem "image_processing", "~> 1.12" # Set of higher-level helper methods for image processing.
gem "jbuilder" # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem "jsbundling-rails"
gem "lograge" # log less so heroku papertrail quits rate limiting our logs
gem "net-smtp", require: false # needed for ruby upgrade to 3.1.0 for some dang reason
gem "net-pop" # needed for ruby upgrade to 3.1.0 https://www.ruby-lang.org/en/news/2021/12/25/ruby-3-1-0-released/
gem "net-imap" # needed for ruby upgrade to 3.1.0 https://www.ruby-lang.org/en/news/2021/12/25/ruby-3-1-0-released/
gem "noticed" # Notifications
gem "paranoia" # For soft-deleting database objects
gem "pdf-forms" # filling in fund request PDFs with user input
gem "rexml" # pdf-forms needs this to deploy to heroku apparently
gem "pg" # Use postgresql as the database for Active Record
gem "pretender"
gem "puma" # Use Puma as the app server
gem "pundit" # for authorization management - based on user.role field
gem "rack-attack" # for blocking & throttling abusive requests
gem "request_store"
gem "sablon" # Word document templating tool for Case Court Reports
gem "scout_apm"
gem "sorbet-runtime" # Type definitions and checking
gem "sprockets-rails" # The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "strong_migrations"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby] # Windows does not include zoneinfo files, so bundle the tzinfo-data gem

group :development, :test do
  gem "bullet" # Detect and fix N+1 queries
  gem "byebug", platforms: %i[mri mingw x64_mingw] # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem "dotenv-rails"
  gem "erb_lint", require: false
  gem "factory_bot_rails"
  gem "pry"
  gem "pry-byebug"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "standard", "1.5.0" # 1.6.0 errors on all factorybot create variables
end

group :development do
  gem "annotate" # for adding db field listings to models as comments
  gem "letter_opener" # Opens emails in new tab for easier testing
  gem "spring" # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring-commands-rspec"
  gem "sorbet" # Type definitions and checking
  gem "tapioca", require: false # Type definitions and checking
  gem "traceroute" # for finding unused routes
  gem "web-console", ">= 3.3.0" # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
end

group :test do
  gem "brakeman" # security inspection
  gem "webmock" # HTTP request stubber
  gem "capybara"
  gem "capybara-screenshot"
  gem "database_cleaner-active_record"
  gem "rails-controller-testing"
  gem "rake"
  gem "selenium-webdriver"
  gem "simplecov"
  gem "webdrivers" # easy installation and use of web drivers to run system tests with browsers
end

# gem "pdf-reader", "~> 2.9"
