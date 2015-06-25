# Ruby on Rails Starter Kit

This template provides a basic [Ruby on Rails](http://rubyonrails.org) application
that includes:

- [Active Record](http://guides.rubyonrails.org/active_record_querying.html)
- [PostgreSQL](http://www.postgresql.org/) for a database
- [Bootstrap](http://getbootstrap.com) for a frontend design framework
- [RSpec](https://github.com/rspec/rspec) for unit testing
- [Shoulda Matchers](https://github.com/thoughtbot/shoulda-matchers) for unit testing
- [Capybara](https://github.com/jnicklas/capybara) for acceptance testing
- [Pry](https://github.com/pry/pry) for debugging

## Getting Started

```no-highlight
# Clone down this template
git clone https://github.com/dan3lson/rails_starter_kit.git <YOUR_APP_NAME>

# Move into your app's directory
cd <YOUR_APP_NAME>

# Install all the gems
bundle install

# Remove the old git history and start your own
rm -rf .git && git init && git add -A && git commit -m 'Initial commit'
```

### Configuring Your Database

This template is set up for using a PostgreSQL database. You will need to update the
`config/database.yml` with your appropriate database names.

Once you've updated the `config/database.yml`, you can create your database with
`rake db:create`.

## Rake Tasks

Rails uses [activerecord](http://guides.rubyonrails.org/active_record_basics.html),
which provides the following rails rake tasks:

```no-highlight
rake db:create            # create the database from config/database.yml from the current Sinatra env
rake db:create_migration  # create an ActiveRecord migration
rake db:drop              # drops the data from config/database.yml from the current Sinatra env
rake db:migrate           # migrate the database (use version with VERSION=n)
rake db:rollback          # roll back the migration (use steps with STEP=n)
rake db:schema:dump       # dump schema into file
rake db:schema:load       # load schema into database
rake db:seed              # load the seed data from db/seeds.rb
rake db:setup             # create the database and load the schema
rake db:test:prepare      # Prepare test database from development schema
```
