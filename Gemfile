#source 'http://rubygems.org'
source :gemcutter

gem "rails", "3.0.3"     

gem "mysql"

# Gem Environments
group :development do 
  gem 'ruby-debug19'
  gem 'jeweler'
end

group :test do
#  gem "redgreen"
  gem 'factory_girl_rails'
  gem 'test-unit'
  # :require=>false allows mocha to correctly modify the test:unit code to add mock() and stub()
  gem "mocha", '=0.9.8', :require=>false
  gem "sqlite3"
end

