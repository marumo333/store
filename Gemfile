# Gemfile
source "https://rubygems.org"

gem "rails", "~> 8.0.2"
gem "propshaft"

# 開発用は SQLite3
gem "sqlite3", "~> 2.1"

# テスト／CI 用は PostgreSQL
gem "pg", "~> 1.4"  # PostgreSQL adapter

gem "puma", "~> 6.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"

gem "tzinfo-data", platforms: %i[windows jruby]

gem "solid_cache"
gem "solid_queue"
gem "solid_cable"

gem "bootsnap", require: false
gem "kamal", require: false
gem "thruster", require: false

group :development do
  gem "web-console"
end

group :development, :test do
  gem "debug", platforms: %i[mri windows], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :test do
  # PostgreSQL adapter (already defined above with version constraint)
  gem "capybara"
  gem "selenium-webdriver"
end
