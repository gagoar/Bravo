source "http://rubygems.org"

platforms :ruby_19 do
  gem "httpi", "0.7.9"
end
gem "curb"
gem "savon"
gem "active_support", ">= 3.0.0"
gem "tzinfo"

group :development do
  platforms :ruby_18 do
    gem "ruby-debug"
  end
  platforms :ruby_19 do
    gem 'ruby-debug-base19', "0.11.24"
    gem 'ruby-debug19', "0.11.6"
  end
  gem "rspec", "~> 2.4.0"
  gem "bundler", ">= 1.0.0"
  gem "jeweler", "~> 1.6.3"
  gem "rcov", ">= 0"
end

