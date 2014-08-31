ReMind
================
ReMind is the Recipe Management system for 'The Vegan Among Us'.

It will have the following basic features upon completion:

* Collection of recipes from users (CRUD with print/export)
* Meal planning (create meal plans/menus, print menus)
* Social Network integration (add recipes to Facebook, Twitter, Pinterest)
* Shopping list creation
* User specific profiles
* Nutritional Information
* Sub-categorize recipes into cuisines


There will be also a way to categorize the recipe such as (but not limited to):

* Breakfast
* Lunch
* Supper
* Tea
* Snack
* Soup
* Appetizer
* Desert
* etc.

As time goes on, there will likely be more added to this - and maybe some removed.  
We'll be building this in an agile fashion, so it will be prioritized, reworked, and running with iterative builds.  
For the short term - I'll be deploying to the free Heroku site, but as it nears a 'prod-like' state, it will be put on 
recipes.theveganamongus.com (in the same hosting service as www.theveganamongus.com)

Rails Components
----------------

Web server: [thin]
Database used: [mysql]
Template engine: [slim]
Test framework: [rspec]
Continuous testing: [guard]
Front-end framework: [bootstrap3]
Sending email: [gmail]
Authentication: [omniauth]
OmniAuth provider: [twitter]
Authorization: [roles]
Page-view analytics: [ga]
Environment variables: [figaro]
Improve error reporting with 'better_errors': [true]
Use 'pry': [true]


Ruby on Rails
-------------

This application requires:

- Ruby 2.1.0
- Rails 4.1.5
- AngularJS 1.2.22

Learn more about [Installing Rails](http://railsapps.github.io/installing-rails.html).

Getting Started
---------------

Documentation and Support
-------------------------

Issues
-------------

Contributing
------------

Credits
-------
This application was generated with the [rails_apps_composer](https://github.com/RailsApps/rails_apps_composer) gem
provided by the [RailsApps Project](http://railsapps.github.io/).

Rails Composer is open source and supported by subscribers. Please join RailsApps to support development of Rails Composer.

License
-------
The MIT License (MIT)