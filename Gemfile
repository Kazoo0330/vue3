source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Core
gem 'rails', '~> 5.1.5'

# Middleware
gem 'sqlite3'
gem 'puma', '~> 3.7'

# Frontend
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'webpacker'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'

# Backend
gem 'jbuilder', '~> 2.5'
# gem 'redis', '~> 4.0'
# gem 'bcrypt', '~> 3.1.7'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'foreman'
# foremanでProcfileから複数のプロセス管理設定

# css settings below
gem 'jquery-rails'
gem 'jquery-turbolinks'
gem 'materialize-sass'
gem 'material_icons'

gem 'haml-rails'
gem 'erb2haml'
# change erb to haml
# run 'haml:convert_erbs' to convert the erb files. not to replace.
