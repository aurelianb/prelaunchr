source 'https://rubygems.org'

ruby '2.5.3'

gem 'activeadmin'
gem 'delayed_job_active_record'
gem 'devise'
gem 'pg'
gem 'rails', '~> 5.2'
gem 'puma'
gem 'bootsnap'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 4.2.2'
  gem 'sass-rails',   '~> 5.0.7'
  gem 'uglifier'
end

group :development do
  gem 'listen'
end

group :development, :test do
  gem 'byebug'
  gem 'rspec-rails', '~> 3.9'
  # gem "dotenv-rails"
end

group :test do
  gem 'rails-controller-testing'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

group :production do
  gem 'rails_12factor'
  gem 'rails_serve_static_assets'
end
