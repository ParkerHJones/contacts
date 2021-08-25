rails new "project_name" -d postgresql --webpack=react
cd project_name
bundle add react-rails
rails g react:install
rails db:create
rails s (starts server)


GEM FILES 

UNDER LINE 31 in GemFile

gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry-rails'
  gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'master'
  
BUNDLE in Iterm after putting into GemFile
