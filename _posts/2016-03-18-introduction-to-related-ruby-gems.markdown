---
layout: post
title:  "2. Introduction to related ruby gems"
date:   2016-03-18 07:31:00 +0200
categories:
- rails-angular
---

Welcome to second part of our series, In this blog I'm going to introduce you some rubygems , we use accordingly.

Our gemfile looks like,

{% highlight bash %}
source 'https://rubygems.org'
ruby '2.2.1'

gem 'rails', '4.2.5.2'
gem 'rails-api'
gem 'spring', :group => :development
gem 'sqlite3'
gem 'friendly_id', '~> 5.1.0'
gem 'rack-cors'
gem 'dalli'
gem 'puma'

gem 'omniauth'
gem 'devise_token_auth'
gem 'active_model_serializers'

group :test do
	gem 'shoulda'
	gem 'mocha'
end

group :development, :test do
	gem 'factory_girl_rails'
	gem 'rspec-rails'
	gem 'rspec-its'
end
{% endhighlight %}

From top to bottom

* `spring`, is a preloader for speed up development for rake tasks
* `friendly_id`, one of my favorites, it makes our url pretty
* `rack-cors`, is middleware for handling cross-origin ajax.
* `dalli`, is a memcache client for ruby
* `puma`, is a web server and allow us multithreading
* `omniauth`, allow us to use third-party login systems.(facebook,github,etc..)
* `devise_token_auth`, one of my favorites, it reduces development time.
* `active_model_serializers`, is allows us to modify of api outputs
* `shoulda`, makes our tests a lot easier.
* `mocha`, for mocking our tests
* `factory_girl_rails`,Replacing the fixtures for testing
* `rspec-rails`, replacing for mini_test
* `rspec-its`, using its syntax of rspec which makes a lot simpler.

To go on -> 3. [Creating angular apps using yeoman][creating-angular-app] (coming soon)

[creating-angular-app]: /blog/rails-angular/creating-angular-apps-using-yeoman
