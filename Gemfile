source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.1'
gem 'rails', '~> 7.0.2', '>= 7.0.2.2'


gem 'jbuilder'
gem 'jwt_sessions', '~> 2.6'
gem 'passenger', '>= 6.0.12', require: 'phusion_passenger/rack_handler'
gem 'pg', '~>1.3'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'bcrypt', '~> 3.1.7'
gem 'bootsnap', require: false
gem 'rack-cors'


# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "redis", "~> 4.0"
# gem "kredis"
#
# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"



group :development, :test do
  gem 'pry', '~> 0.10.3'
end

group :test do
  gem 'rspec', '~> 3.4'
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  gem 'spring'
end

