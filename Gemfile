source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.1'
gem 'rails', '~> 6.1.3', '>= 6.1.3.1'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'pagy', '~> 4.2'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'rswag'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'master'
end

group :development do
  gem 'listen', '~> 3.3'
  gem "rspec-rails"
  gem 'spring'
end

