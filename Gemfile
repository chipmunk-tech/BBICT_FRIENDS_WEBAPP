source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.4"
gem 'sassc'
gem 'webpacker'
gem "rails", "~> 7.0.6"
gem "sprockets-rails"

gem 'devise', '~> 4.9', '>= 4.9.2'
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", "~> 4.0"
gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
  gem "sqlite3", "~> 1.4"
  # gem "spring"
end

group :production do
  gem 'pg', '~> 1.5', '>= 1.5.3'  
  #gem 'rails_12factor', '0.0.2'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
