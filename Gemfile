source "http://rubygems.org"

gemspec

gem "kaminari"
gem "rails", "~> 4.0.13"
gem "sqlite3"
gem "jquery-rails"

group :development do
  platforms :mri_19 do
    gem "debugger"
  end
  gem 'guard-rspec'
end

group :development, :test do
  gem 'rspec-rails'
end
group :test do
  gem "cucumber"
  gem "cucumber-rails"
  gem "capybara"
  gem "launchy"
  gem "database_cleaner"
  gem 'rspec'
end
# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19'
