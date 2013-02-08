source 'https://rubygems.org'
gem 'rails', '3.2.11'
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'jquery-ui-rails'
end
gem 'jquery-rails'
gem "thin", ">= 1.5.0"
gem "mysql2", ">= 0.3.11"
gem "devise", ">= 2.1.2"
gem "cancan", ">= 1.6.8"
gem "rolify", ">= 3.2.0"
gem 'bootstrap-sass'
gem 'font-awesome-rails', :git => 'git://github.com/bokmann/font-awesome-rails.git'
gem "simple_form", ">= 2.0.3"
gem "therubyracer", "= 0.10.2", :group => :assets, :platform => :ruby
gem "chef", path: './lib/chef'
gem 'sidekiq'
gem 'sinatra', require: false
gem 'slim'

gem 'cloudster', "~> 2.19.3"

group :development, :test do
  gem "awesome_print"
  gem "debugger"
  gem "spork"
end

group :development do
  gem "better_errors"
  gem "binding_of_caller"
end

group :test do
  gem 'test-unit', :require => "test/unit"
  gem "rspec-rails", ">= 2.11.0"#, :group => [:development, :test]
  gem "factory_girl_rails", ">= 4.1.0"#, :group => [:development, :test]
  gem 'shoulda'
  gem "mock_redis"
  gem 'shoulda-matchers'
end
