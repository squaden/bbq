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
gem 'puma', '~> 4.3'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'resque', '~> 2.0'
gem 'pundit'
gem 'omniauth'
gem 'omniauth-vkontakte'

group :development, :test do
  gem 'sqlite3'
  gem 'pry-rails'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rspec-rails', '~> 3.4'
  gem 'factory_bot_rails'
  gem 'shoulda-matchers'
end

group :development do
  gem 'capistrano', require: false
  gem 'capistrano-rails', require: false
  gem 'capistrano-passenger', require: false
  gem 'capistrano-rbenv', require: false
  gem 'capistrano-bundler', require: false
  gem 'letter_opener', require: false
  gem 'capistrano-resque', require: false
  gem 'ed25519', '>= 1.2', '< 2.0', require: false
  gem 'bcrypt_pbkdf', '>= 1.0', '< 2.0', require: false

end

group :production do
  gem 'pg'
end
