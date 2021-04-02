source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.6'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.3'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# A fast JSON:API serializer for Ruby Objects.
gem 'jsonapi-serializer'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # debugger
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'pry'
  gem 'pry-remote'

  # specs
  gem 'rspec-rails'
  gem 'action-cable-testing'
  gem 'factory_bot_rails'
  gem 'faker', require: false
  gem 'timecop'
  gem 'webmock'
  gem 'database_cleaner-active_record'

  # Env vars
  gem 'dotenv-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'derailed_benchmarks'
  gem 'memory_profiler'
  gem 'annotate'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'spring-commands-rspec'
  gem 'spring-commands-rubocop'
  gem "faraday-detailed_logger"

  # better errors
  gem 'better_errors'
  gem 'binding_of_caller'

  # Code linting
  gem 'rubocop', '~> 0.93.1'
  gem 'rubocop-rails'
  gem 'rubocop-performance'

  # Security
  gem 'brakeman'
  gem 'bundle-audit'
end

# Authentication
gem 'devise'
gem 'devise_invitable'
gem 'simple_token_authentication'
gem 'omniauth-facebook'

# Pagination
gem 'pagy'

# JWT Tokens
gem 'jwt'

# Permissions / Authorization
gem 'pundit'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
