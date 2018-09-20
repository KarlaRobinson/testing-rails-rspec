## Pluralsight Rspec TDD tutorial
### https://app.pluralsight.com/player?course=test-driven-rails-rspec-capybara-cucumber&author=rem-zolotykh&name=test-driven-rails-rspec-capybara-cucumber-m3&clip=1&mode=live

* Ruby version: 2.5.1

* Gems: 'bootstrap-sass', 'simple_form'

* Test gems: 'capybara'

* Development & Test gems:
- 'rspec-rails'
- 'factory-bot'
- 'spring'
- 'spring-commands-rspec'

* Configuration

* Database creation

* Database initialization

* Test suite: bin/rspec

* Deployment: rails s

* The helpers, mailers, and models directories are meant to hold tests for view helpers, mailers, and models, respectively. The controllers directory is meant to hold tests for controllers, routes, and views. The integration directory is meant to hold tests for interactions between controllers.

* The system test directory holds system tests, which are used for full browser testing of your application. System tests allow you to test your application the way your users experience it and help you test your JavaScript as well. System tests inherit from Capybara and perform in browser tests for your application.

* Fixtures are a way of organizing test data; they reside in the fixtures directory.

* A jobs directory will also be created when an associated test is first generated.

* The test_helper.rb file holds the default configuration for your tests.

* The application_system_test_case.rb holds the default configuration for your system tests.
