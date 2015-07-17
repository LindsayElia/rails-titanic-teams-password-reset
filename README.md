# Superheros!

Your application should have the following behavior at a minimum:

  * Anyone can visit the root page and see a list of all the teams
  * Anyone can click on a team to view its superheroes
  * Only a logged in user can create a new team
  * Only a logged in user can add superheroes to a team
  * Only an admin can create/update and delete superheroes (think about adding a boolean called is_admin in your users table)
 
Each User should have a/an
  * username
  * password
  * password_digest
  * is_admin (this should default to false)

Each Team should have a/an:
  * name (i.e. "Avengers")
  * description

Each Superhero should have a/an:
  * name
  * height
  * bio
  * image_url

For this assignment - many teams can have many superheroes - this means you need to set up a many to many association. Also, one user can make many teams.

The routing, and views are completely up to you, just remember that the teams resource needs to be nested inside of users. With that said, this assignment is meant to build on all the things you've been learning up to this point: resources, associations, authentication, etc.

## Getting Started

1. Create a new rails application
2. Include necessary gems in your Gemfile and run `bundle` (this includes gems for testing!)
3. Run rake db:create
4. Generate your models and migrations
5. Set up the necessary associations
6. Run rake db:migrate
7. Test Your Models! (write specs that ensure your validations, associations are set up correctly and make sure that instances of your models respond_to everything in your migration!)
7. Use before_actions for repeated code
8. Use partials and shared/errors
9. Style the app

## Bonus

 * Add a powers resource that has many to many relationship to superheroes (superman has super_strength, hulk has super_strength etc)
