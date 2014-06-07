source 'https://rubygems.org'
ruby "2.1.2"

gem 'rails', '4.1.1'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'bootstrap-sass', '~> 3.1.1'
gem "paperclip", :git => "git://github.com/thoughtbot/paperclip.git"
gem "paperclip-dropbox", ">= 1.1.7"
gem "figaro"

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

group :development, :test do
	gem 'sqlite3' 
end 

group :doc do
	gem 'sdoc', require: false
end