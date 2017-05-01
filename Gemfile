source 'https://rubygems.org'

gem 'rails', '4.2.6'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'bootstrap-sass', '~> 3.3.6'
gem 'devise'
gem 'toastr-rails'
gem 'omniauth-facebook', '4.0.0'
gem "paperclip", "~> 5.0.0.beta1"
gem 'dropzonejs-rails'
gem "figaro", "~> 1.1.0"
gem 'aws-sdk', '~> 2.3'
gem 'geocoder'
gem 'jquery-ui-rails'
gem 'stripe'

gem "private_pub"
gem "thin"

gem 'ransack'



group :production do 
	gem 'pg'
	gem 'rails_12factor'
end

group :development, :test do 
	gem 'sqlite3'
end



group :development, :test do
  gem 'pry-rails'  # rails console(もしくは、rails c)でirbの代わりにpryを使われる
  gem 'pry-doc'    # methodを表示
  gem 'pry-byebug' # デバッグを実施(Ruby 2.0以降で動作する)
  gem 'pry-stack_explorer' # スタックをたどれる
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end