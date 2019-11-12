source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.3'
gem 'devise'
gem 'devise-i18n'
gem 'russian'
gem 'rails-i18n', '~> 5.1'
gem 'twitter-bootstrap-rails'
gem "font-awesome-rails"
gem 'carrierwave'
gem 'rmagick'
gem 'fog-aws'
gem 'uglifier', '>= 1.3.0'
gem 'puma', '~> 3.11'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'resque', '~> 2.0'
gem 'rspec-rails', '~> 3.4'

group :development, :test do
  gem 'sqlite3'
  gem 'pry-rails'
  gem 'listen', '>= 3.0.5', '< 3.2'
end

group :development do
  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano-passenger'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'letter_opener'
  gem 'capistrano-resque'
end

group :production do
  gem 'pg'
end
