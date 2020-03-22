source 'http://rubygems.org'

gem 'rails', '4.0.0'
ruby '1.9.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :test do
  gem 'cucumber-rails', '>= 1.4.0', :require => false
  gem 'cucumber-rails-training-wheels', '>= 1.0.0'
  gem 'rspec-rails', '>= 2.14.0'
  gem 'simplecov'
end
group :development, :test do
  gem 'sqlite3'
  gem 'debugger'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'launchy'

end
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'therubyracer'
  gem 'sass-rails', '~> 4.0.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier', '>= 2.3.2'
end

gem 'jquery-rails', '>= 3.0.4'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
gem 'haml'
