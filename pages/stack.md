#Getting started

###Demo
Simple step to create demo RoR app:
```
cd somewhere
rails new demo
cd demo
rails server //deploy to server
```
Then open browser at [http:\\localhost:3000](http:\\localhost:3000).

###Hello, Rails!
Create new **controller**:

    rails generate controller {ControllerName} {action1} {action2}
Ex:

    rails generate Say hello goodbye
    
We get output:

    create  app/controllers/say_controller.rb
	route  get 'say/goodbye'
	route  get 'say/hello'
	invoke  erb
	create    app/views/say
	create    app/views/say/hello.html.erb
	create    app/views/say/goodbye.html.erb
	invoke  test_unit
	create    test/controllers/say_controller_test.rb
	invoke  helper
	create    app/helpers/say_helper.rb
	invoke    test_unit
	create      test/helpers/say_helper_test.rb
	invoke  assets
	invoke    coffee
	create      app/assets/javascripts/say.js.coffee
	invoke    scss
	create      app/assets/stylesheets/say.css.scss
