source 'https://rubygems.org'
ruby '2.4.0'

gem 'rails', '~> 5.0.1'
gem 'puma'
gem 'mysql2'

gem 'listen'
gem 'uglifier'
gem 'autoprefixer-rails'
gem 'mini_racer', platforms: :ruby
gem 'turbolinks'
gem 'sprockets-rails', :require => 'sprockets/railtie'

gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'rails-ujs'

gem 'sass-rails'

gem 'slim-rails', '3.1.3'
gem 'jbuilder', '~> 2.5'

#gem 'bootstrap', '~> 4.0.0'
gem 'bootstrap-sass'

gem 'config'
gem 'settingslogic'
gem 'dotenv-rails'
gem 'beautiful-log'

gem 'active_decorator'

gem "paranoia", github: "rubysherpas/paranoia", branch: "rails5"
gem 'enumerize'

gem 'devise'

gem 'omniauth'
gem 'omniauth-facebook'

gem 'whenever', :require => false

gem 'mini_magick'
gem 'carrierwave'

gem 'fog'
gem "asset_sync"

gem 'kaminari'
gem 'ransack'

gem 'safe_attributes'

gem 'google_drive'
gem 'slack-notifier'

gem 'letter_opener_web'
# i18n
gem 'rails-i18n', '~> 5.1'
gem 'devise-i18n'

group :development do
  gem 'spring'

  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-byebug'
  gem 'pry-stack_explorer'

  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano3-puma'
  gem 'capistrano-rbenv', github: "capistrano/rbenv"
end

group :test do
  gem 'rspec-rails'
  gem "rails-controller-testing"
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'turnip'
  gem "capybara"
  gem 'capybara-webkit'
  gem 'selenium-webdriver'
end

group :development, :test, :staging do
  gem 'seed-fu'
end
