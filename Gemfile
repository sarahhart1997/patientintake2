source 'https://rubygems.org'

# Specify your Rails version
gem 'rails', '~> 6.1.4'

# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.5.0', '< 0.7.0'

# Use Puma as the app server
gem 'puma', '~> 3.12'

# Use Bootstrap for styling
gem 'bootstrap', '~> 4.5', '>= 4.5.2'

# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'

# Use webpacker for app-like JavaScript in Rails
gem 'webpacker', '~> 6.0.0.rc.6'

# Turbolinks makes navigating your web application faster
gem 'turbolinks', '~> 5'

# Use Jbuilder for JSON APIs
gem 'jbuilder', '~> 2.7'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Use Active Storage variant
gem 'mini_magick', '~> 4.11'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

# Use dotenv for environment variable management
gem 'dotenv-rails', groups: [:development, :test]

# Use RSpec for testing
group :test do
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'faker'
end

# Use Capybara for feature tests
group :development, :test do
  gem 'capybara'
  gem 'selenium-webdriver'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Bootsnap helps with faster boot times
gem 'bootsnap', '>= 1.4.2', require: false

# Spring speeds up development by keeping your application running in the background
gem 'spring'

# Uncomment if you have the 'spring-watcher-listen' gem
# gem 'spring-watcher-listen', '~> 2.0.0'

# Add PG gem for PostgreSQL in production
group :production do
  gem 'pg'
end
