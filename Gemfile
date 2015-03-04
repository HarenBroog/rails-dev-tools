source 'https://rubygems.org'

ruby '2.2.0'

group :standard do
  gem 'rails'
  gem 'pg'
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'jquery-rails'
  gem 'haml-rails'
  gem 'uglifier'
end

group :front_end do
  gem 'bower-rails'
  gem 'bootstrap-sass'
  gem 'bourbon'
  gem 'font-awesome-sass'
end

group :back_end do
  gem 'cancan'
  gem 'carrierwave'
  gem 'decent_exposure'
  gem 'devise'
  gem 'draper'
  gem 'fog' #carrierwave + S3
  gem 'simple_form'
end

group :misc do
  gem 'rollbar'
  gem 'turbolinks'
end

group :server do
  gem 'unicorn'

group :production do
  gem 'rails_12factor' #for heroku
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'did_you_mean'
  gem 'guard'
  gem 'guard-rspec'
  gem 'jazz_hands'
  gem 'spring'
end

group :development, :test do
  gem 'dotenv-rails'
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end
