---
layout: post
title:  "1. Creating api with rails-api gem"
date:   2016-03-17 05:31:00 +0200
categories:
- rails-angular
---

Welcome to first part of our series, I'm going to show you the `rails-api` gem.
Which is merged into rails, you can use it when rails 5 is published.(or beta now)
From original repo,

>Rails::API is a subset of a normal Rails application, created for applications that don't require all functionality that a complete Rails application provides. It is a bit more lightweight, and consequently a bit faster than a normal Rails application. The main example for its usage is in API applications only, where you usually don't need the entire Rails middleware stack nor template generation.


to install, in your terminal `gem install rails-api`, then create a new application using,

`rails-api new api-name`, this will generate your new application.

You will see the folder structure that a lot cleaner than regular rails,meanwhile we won't need them at all.


To go on -> 2. [Introduction to related ruby gems][introduction-to-related-ruby-gems]

[introduction-to-related-ruby-gems]: /blog/rails-angular/introduction-to-related-ruby-gems