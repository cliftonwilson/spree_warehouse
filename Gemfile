source 'http://rubygems.org'

gemspec

gem 'spree', '1.1.1' 

gem 'pdfkit'
gem 'wkhtmltopdf-binary'

group :development, :test do 
  gem "sass", :require => 'sass' 
end

group :test do
  gem 'rspec-rails', '~> 2.9.0'
  gem 'factory_girl_rails', '~> 1.7.0'
  gem 'ffaker'
  gem 'shoulda-matchers', '~> 1.0.0'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'database_cleaner', '0.7.1'
  gem 'launchy'
  
  gem 'guard'
  gem 'guard-rspec', '~> 0.6.0'
  gem 'guard-bundler'
end

unless ENV["CI"]
  platform :ruby_18 do
    gem 'rcov'
    gem 'ruby-debug'
  end
  platform :ruby_19 do
    gem 'simplecov'
    gem 'ruby-debug19'
  end
end

