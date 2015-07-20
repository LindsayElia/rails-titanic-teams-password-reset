# Homework - Adding Password Reset To Our Applications with Rails

Implement password reset functionality in the weekend assignment. You can start by forking and cloning the solution branch here - [https://github.com/gSchool/rails-titanic-teams](https://github.com/gSchool/rails-titanic-teams)

# Getting started:

1. Run rails g rspec:install
2. Create a feature test (either by generating one or manually creating a features folder and inside a test file)
3. Install the capybara-email gem
4. Add `require 'capybara/email/rspec' to your spec_helper
5. Create a feature test for password reset.
6. Get the tests to pass!

# To make your tests pass

1. Add the necessary columns to your users table
2. Run your migrations
3. Add the necessary logic in your user.rb model to generate a token
4. Generate a mailer and a corresponding view and add the code necessary
5. Generate a controller to handle the new, create,edit,update actions for password reset
6. Make sure you have the necessary routes to handle these actions
7. Write the code necessary in your controllers to make the tests pass!

# Bonus

1. Incorporate some additional logic to make sure that tokens expire after a certain amount of time
2. Configure Mandrill so you can see your emails!

# Super Bonus
1. Refactor your code using Rails verifiers. You can see an example here - [https://github.com/gSchool/rails_password_reset_example/tree/verifiers](https://github.com/gSchool/rails_password_reset_example/tree/verifiers)
