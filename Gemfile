source 'https://rubygems.org'
ruby '2.1.2'

gem 'rails', '4.1.6'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development
gem 'bootstrap-sass'
gem 'did_you_mean', group: [:development, :test]
gem 'devise', '~> 3.4.0'

group :development, :test do
  gem 'sqlite3'
end

group :development do
  gem 'rb-fsevent'#, :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'guard-livereload', require: false
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
