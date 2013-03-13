source 'https://rubygems.org'

gem 'rails', '3.2.12'
gem 'jquery-rails'

# Heroku doesn't work too well with sqlite. it needs something
# called postgreSQL or a PG command line.

group :production do
	gem 'pg'
end

group :development, :test do
	gem 'sqlite3'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
gem 'uglifier', '>= 1.0.3'
end
