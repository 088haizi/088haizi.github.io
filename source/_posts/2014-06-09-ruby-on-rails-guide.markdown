---
layout: post
title: "Ruby on Rails Guide 笔记"
date: 2014-06-09 23:52:33 +0800
comments: true
categories: 
---
其实吧，这就是篇文档笔记，自己看文档总是感觉看着看着，就变得像抄代码了，也不知道自己写的是什么，可能因为是自己之前没有什么 web 的经验，所以现在把里面的代码择都出来，并且说明，方便自己理解。

1.  Creating a New Rails Project
	*  Installing Rails
	
		```
		$ ruby -v
		ruby 2.0.0p353
		$ sqlite3 --version
		$ gem install rails
		$ rails --version
		```
	*  Creating the Blog Application
	
		```
		$ rails new blog
		```
2.  Hello Rails!
	*  Starting up the Web Server
	
		```
		$ rails server (--port=3000 可选)
	 	```
	*  Say "Hello", Rails
	
		```
		$ rails generate controller welcome index
		create  app/controllers/welcome_controller.rb
		 route  get 'welcome/index'
		invoke  erb
		create    app/views/welcome
		create    app/views/welcome/index.html.erb
		invoke  test_unit
		create    test/controllers/welcome_controller_test.rb
		invoke  helper
		create    app/helpers/welcome_helper.rb
		invoke    test_unit
		create      test/helpers/welcome_helper_test.rb
		invoke  assets
		invoke    coffee
		create      app/assets/javascripts/welcome.js.coffee
		invoke    scss
		create      app/assets/stylesheets/welcome.css.scss
		```
		➔  app/views/welcome/index.html.erb
		
		```		
		<h1>Hello, Rails!<1>
		```
	*  Setting the Application Home Page
	
		➔  config/routes.rb
		
		```
		root 'welcome#index'
		```
3.  Getting Up and Running
    *  Laying down the ground work
    
    	1. Creat a controller
	    	
	    	
	    	```
	    	$ rails g controller articles
	    	```
    	
    	2. Define a new method
	    	
	    	➔  app/controllers/articles_controller.rb
	    	
	    	```
	    	def new
			end
	    	```
    	    	
    	3. Create a new file at app/views/articles/new.html.erb
    	
	    	➔  app/views/articles/new.html.erb
	    	
	    	```
	    	<h1>New Article</h1>
	    	```
    	
    *  The first form
    	
    	1. To create a form
    	2. 
   	     	
    *  Creating articles
    *  Creating the Article model
    *  Running a Migration
    *  Saving data in the controller
    *  Showing Articles
    *  Listing all articles
    *  Adding links
    *  Adding Some Validation
    *  Using partials to clean up duplication in views
    *  Deleting Articles
4.  Adding a Second Model
	*  Generation a Model
	*  Associating 	Models
	*  Adding a Route for Comments
	*  Generation a Controller
5.  Refactoring
	*  Rendering Partial Collections
	*  Rendering a Partial Form
6.  Deleting Comments
7.  Security
	*  Basic Authentication
	*  Other Security Considerations
	
持续更新中。。。