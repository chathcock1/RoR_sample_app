source "https://rubygems.org"

ruby "3.2.2"
gem "rails", "~> 7.1.2" # Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "bootstrap-sass", "3.4.1"
gem "sassc-rails", "2.1.2"
gem "sprockets-rails", "3.4.2" # The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
# gem "sqlite3", "~> 1.4" # Use sqlite3 as the database for Active Record
gem "pg", "~>1.5" # heroku uses postgresql database, not sqlite3
gem "puma", ">= 5.0" # Use the Puma web server [https://github.com/puma/puma]
gem "importmap-rails" # Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "turbo-rails" # Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "stimulus-rails" # Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "jbuilder" # Build JSON APIs with ease [https://github.com/rails/jbuilder]
# Use Redis adapter to run Action Cable in production
# gem "redis", ">= 4.0.1"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

gem "tzinfo-data", platforms: %i[ windows jruby ] # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "bootsnap", "~>1.12", require: false # Reduces boot times through caching; required in config/boot.rb

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara",                   "3.39.2"
  gem "selenium-webdriver",         "4.2.0"      
  gem "webdrivers",                 "5.0.0"
  gem "rails-controller-testing",   "1.0.5"
  gem "minitest",                   "5.20.0"
  gem "minitest-reporters",         "1.5.0"
  gem "guard",                      "2.18.0"
  gem "guard-minitest",             "2.4.6"
end