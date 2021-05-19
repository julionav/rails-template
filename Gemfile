source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.6.0"

# Base stack
gem "rails", "~> 6.0.3"
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 4.3"

# Asset management
gem "sass-rails", ">= 6"
gem "webpacker", "~> 4.0"

gem "turbolinks", "~> 5"

# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.2", require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]

  # Seed manager https://github.com/vigetlabs/sprig
  gem "sprig", "~> 0.3.0"

  # Fake data creator
  gem "factory_bot_rails"
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.2"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"

  # Annotates model schema on their own file
  gem "annotate"

  # Better error page
  gem "better_errors"
  gem "binding_of_caller"

  # Lint + formatting
  gem "standard", "~> 0.4.0"
  gem "lefthook"

  # Teesting
  gem "rspec-rails", "~> 4.0.0"
end

group :test do
  gem "shoulda-matchers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
