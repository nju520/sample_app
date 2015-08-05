source 'https://ruby.taobao.org'
ruby '2.2.2'

#gem 'rails', '4.0.4'
# because in chapter 10, I occured an error :
# Failures:

#   1) User micropost associations should destroy associated microposts
#      Failure/Error: @user.destroy
#      NoMethodError:
#        undefined method `name' for nil:NilClass
#      # ./spec/models/user_spec.rb:133:in `block (3 levels) in <top (required)>'
# They suggest that insert following code
gem 'rails', '4.1.2'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '2.13.1'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails', '4.2.1'
end

gem 'sass-rails', '4.0.1'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '2.2.1'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
end

gem 'test-unit'
gem 'minitest'
# install bootstrap
# gem 'bootstrap-sass', '2.3.2.0' download this file and lint to the appliaction.html.erb file
gem 'bcrypt-ruby', '3.1.2'
    
gem 'bootstrap-sass', '~> 3.0.3.0' 
gem 'faker', '1.1.2'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'

# I should add this gem .   
#.field_with_errors" failed to @extend ".control-group".
#The selector ".control-group" was not found.
#Use "@extend .control-group !optional" if the extend should be able to fail.