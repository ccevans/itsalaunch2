source 'https://rubygems.org'

ruby '2.1.5'

gem 'rails', '4.2.0'

gem 'activeadmin', github: 'activeadmin'
gem 'delayed_job_active_record', '~> 4.0.3'
gem 'devise'
gem 'inherited_resources', github: 'josevalim/inherited_resources'

gem 'tzinfo-data', platforms: [:mingw, :mswin]
gem 'coffee-script-source', '1.8.0'
gem 'childprocess', '~> 0.5.9'

group :assets do
  gem 'coffee-rails', '~> 4.1.0'
  gem 'sass-rails',   '~> 5.0.1'
  gem 'uglifier'
end

group :development do
  gem 'pry'
  gem 'sqlite3'
end

group :development, :test do
  gem "dotenv-rails"
end

group :production do
	gem 'pg'
  gem 'rails_12factor'
  gem 'rails_serve_static_assets'
end
