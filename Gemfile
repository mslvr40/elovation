source 'https://rubygems.org'

ruby '2.7.6'

gem 'rails', '~> 5.1'


gem 'sass-rails', '~> 5.0'
gem 'jquery-rails'
gem 'coffee-rails'
gem 'uglifier'
gem 'chartkick'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# This is necessary for running on linux
gem 'therubyracer', platforms: :ruby

gem 'dynamic_form'
gem 'elo'
gem 'trueskill', git: 'https://github.com/saulabs/trueskill', require: 'https://github.com/saulabs/trueskill'

group :production do
  gem 'unicorn'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'listen'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry'
  gem 'pry-byebug'
  gem 'pry-coolline'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test do
  gem 'mocha'
  gem 'rspec-rails', '~> 3.5'
  gem 'timecop'
  gem 'codeclimate-test-reporter', require: nil
  gem 'rails-controller-testing'
end
