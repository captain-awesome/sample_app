source 'https://rubygems.org'

gem 'rails',								'4.2.0'
gem 'sqlite3'
gem 'sass-rails',						'~> 5.0'
gem 'uglifier',							'>= 1.3.0'
gem 'coffee-rails',					'~> 4.1.0'

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder',							'~> 2.0'
gem 'sdoc',									'~> 0.4.0', group: :doc

gem 'bootstrap-sass',       '3.2.0.0'

group :test do
  gem 'minitest-reporters', '1.0.5'
  gem 'mini_backtrace',     '0.1.3'
  gem 'guard-minitest',     '2.3.1'
  gem 'bcrypt',             '3.1.7'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
  gem 'pg',             '0.17.1'
  gem 'rails_12factor', '0.0.2'
  gem 'puma',           '2.11.1'
end