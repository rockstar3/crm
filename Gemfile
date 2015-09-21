source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'


gem 'rails_admin', :git => 'git://github.com/sferik/rails_admin.git'
gem 'devise', '1.4.8'
gem 'cancan', '1.6.7'
gem "compass", '0.11.5'
gem 'jquery-rails', '1.0.16'
gem 'modernizr-rails', '2.0.6'
gem "haml", '3.1.3'
gem 'haml-rails', '0.3.4'
gem 'html5-boilerplate', '1.0.0'
gem 'friendly_id', '3.3.0.1'
gem 'kaminari', '0.12.4'
gem 'acts_as_commentable', '3.0.1'
gem 'therubyracer', '0.9.4'
gem 'paperclip', '2.4.4'
gem 'spreadsheet', '0.6.5.9'
gem 'meta_search', '1.1.1'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
#  gem 'sass-rails', "  ~> 3.1.0"
#  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'

group :production do
#  gem 'mysql2', '0.3.7'
end

group :test, :development do
  gem 'faker'
  # Pretty printed test output
  gem 'turn', :require => false
  gem "rspec-rails", "~> 2.0"
  gem 'factory_girl_rails'
  gem "autotest"
  gem "capybara"
  gem 'simplecov'
  #gem 'metric_fu'
  gem 'mysql'
  #gem 'thin'
  gem 'sqlite3', '1.3.4'
  gem 'annotate',
    :git => 'git://github.com/jeremyolliver/annotate_models.git',
    :branch => 'rake_compatibility'
  gem 'ruby-debug19', :require => 'ruby-debug'
end
