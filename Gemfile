source 'https://rubygems.org'

ruby "2.0.0"

gem 'rails', '4.0.0.rc2'
gem 'sass-rails', '~> 4.0.0'
gem 'sprockets', '2.11.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'bootstrap-sass'
gem 'devise', '~> 3.4.1'
gem 'paperclip', '~> 3.0'
gem 'aws-sdk', '~> 1.59.0'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
     gem 'sqlite3'
end

group :production do
     gem 'pg'
     gem 'rails_12factor'
end