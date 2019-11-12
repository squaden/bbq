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
  gem 'capistrano', '~> 3.8'
  gem 'capistrano-rails', '~> 1.2'
  gem 'capistrano-passenger', '~> 0.2'
  gem 'capistrano-rbenv', '~> 2.1'
  gem 'capistrano-bundler', '~> 1.2'
  gem 'letter_opener'
end

group :production do
  gem 'pg'
end
