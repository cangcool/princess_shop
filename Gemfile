source 'https://rubygems.org'
# ruby version
ruby '2.1.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.6'
# Development and Test tools
# use pg as interface to the PostgreSQL RDBMS
# Use Rspec as Test-Driven Development, Domain Driven Design, and Acceptance Test-Driven Planning
group :development, :test do
  gem 'pg', '0.15.1'
  gem 'rspec-rails', '2.13.1'
end
# Production tools
# use pg as interface to the PostgreSQL RDBMS
# use rails_12factor to run app easier
group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]


gem 'spree', '2.3.4'
gem 'spree_gateway', :git => 'https://github.com/spree/spree_gateway.git', :branch => '2-3-stable'
gem 'spree_auth_devise', :git => 'https://github.com/spree/spree_auth_devise.git', :branch => '2-3-stable'
gem 'spree_fancy', :git => 'git://github.com/spree/spree_fancy.git', :branch => '2-3-stable'