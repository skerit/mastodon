# frozen_string_literal: true

source 'https://rubygems.org'
ruby '>= 2.3.0', '< 2.5.0'

gem 'pkg-config'

gem 'rails', '~> 5.2.4', '>= 5.2.4.2'
gem 'sass-rails', '~> 5.0', '>= 5.0.6'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails', '>= 4.3.1'
gem 'puma'

gem 'hamlit-rails', '>= 0.2.0'
gem 'pg'
gem 'pghero'
gem 'dotenv-rails', '>= 2.2.2'
gem 'font-awesome-rails', '>= 4.7.0.4'
gem 'best_in_place', '~> 3.0.3'

gem 'paperclip', '~> 5.1'
gem 'paperclip-av-transcoder'
gem 'aws-sdk', '>= 2.0'

gem 'addressable'
gem 'devise', '>= 4.4.2'
gem 'devise-two-factor', '>= 3.0.0'
gem 'doorkeeper', '>= 4.2.5'
gem 'fast_blank'
gem 'goldfinger'
gem 'hiredis'
gem 'htmlentities'
gem 'http'
gem 'http_accept_language'
gem 'httplog'
gem 'kaminari', '>= 1.0.1'
gem 'link_header'
gem 'nokogiri'
gem 'oj'
gem 'ostatus2', '~> 1.1'
gem 'ox'
gem 'rabl'
gem 'rack-attack'
gem 'rack-cors', require: 'rack/cors'
gem 'rack-timeout'
gem 'rails-i18n', '>= 5.0.3'
gem 'rails-settings-cached', '>= 0.6.5'
gem 'redis', '~>3.2', require: ['redis', 'redis/connection/hiredis']
gem 'rqrcode'
gem 'ruby-oembed', require: 'oembed'
gem 'sidekiq'
gem 'sidekiq-unique-jobs'
gem 'simple-navigation'
gem 'simple_form', '>= 4.0.0'
gem 'sprockets-rails', '>= 3.2.0'
gem 'statsd-instrument'
gem 'twitter-text'
gem 'tzinfo-data'
gem 'whatlanguage'

gem 'react-rails', '>= 1.11.0'
gem 'browserify-rails', '>= 4.3.0'
gem 'autoprefixer-rails'

group :development, :test do
  gem 'rspec-rails', '>= 3.5.2'
  gem 'pry-rails'
  gem 'fuubar'
  gem 'fabrication'
  gem 'i18n-tasks', '~> 0.9.13'
end

group :test do
  gem 'capybara'
  gem 'faker'
  gem 'microformats2', '>= 2.1.0'
  gem 'rails-controller-testing', '>= 1.0.1'
  gem 'rspec-sidekiq'
  gem 'simplecov', '>= 0.14.1', require: false
  gem 'webmock'
end

group :development do
  gem 'rubocop', require: false
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener'
  gem 'letter_opener_web', '>= 1.3.1'
  gem 'bullet'
  gem 'active_record_query_trace'

  gem 'capistrano', '3.8.0'
  gem 'capistrano-rails'
  gem 'capistrano-rbenv'
  gem 'capistrano-yarn'
  gem 'capistrano-faster-assets', '~> 1.0'
end

group :production do
  gem 'rails_12factor'
  gem 'redis-rails', '>= 5.0.2'
  gem 'lograge', '>= 0.9.0'
end
