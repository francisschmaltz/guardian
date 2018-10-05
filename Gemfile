source 'https://rubygems.org'

gem 'rails', '~> 5.0.0'
gem 'mysql2', '>= 0.4.10', '< 0.5'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'bcrypt', '~> 3.1.7'
gem 'haml'
gem 'nifty-utils'
gem 'nilify_blanks'
gem 'authie'
gem 'dynamic_form'
gem 'hashie'
gem 'foreman'
gem 'omniauth'
gem 'omniauth-cas'

require_relative './lib/guardian/config'
if Guardian.yaml_config['auth'] && strategy = Guardian.yaml_config['auth']['strategy']
  gem "omniauth-#{strategy}"
end

group :development, :test do
  gem 'byebug'
  gem 'annotate'
end
