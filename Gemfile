source 'https://rubygems.org'

ruby '2.4.1'

gem 'pg'
gem 'rake'
gem 'rails', '~> 5.0'
gem 'nokogiri'
gem 'active_model_serializers', '~> 0.9.3'
gem 'rack-cors', require: 'rack/cors'
gem 'newrelic_rpm'
gem 'redis'
gem 'kaminari'

group :development, :test do
  gem 'pry'
end

group :test do
  gem 'rspec-rails'
  gem 'factory_girl'
  gem 'factory_girl_rails', '~> 4.0'
  gem 'codeclimate-test-reporter', require: nil
  gem 'fakeredis'
end

group :production do
  gem 'rails_12factor'
  gem 'uglifier'
  gem 'puma'
end
