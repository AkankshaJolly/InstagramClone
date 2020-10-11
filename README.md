# InstagramClone

This project runs on ruby 2.7.4

### Getting started

* Ruby version
2.7.1

* System dependencies
See Gemfile

* Configuration
  * Install bundler: https://bundler.io/
  * Install homebrew: https://docs.brew.sh/Installation
  * Install rbenv: `brew install rbenv`
  * Install ruby: `rbenv install 2.7.1`
  * Install gems: `bundle install` or `./bin/setup`
  * Install npm: https://www.npmjs.com/get-npm
  * Install node: `npm install`

* Database creation
`bundle e rails db:setup`

* Database initialization
  * `sudo -u postgres createuser --superuser <your-username>`
  * `./bin/setup`

* How to test app
  * `rails server`
  * Visit url displayed after "Listening" in the output of the above command

* How to run the test suite
  * `rake test:controllers`
  * `rake test:models`

* Services (job queues, cache servers, search engines, etc.)
  * ## TODO: Fill in this section

* Deployment instructions
  * ## TODO: Fill in this section

* ...

To get the Rails server running locally:

- Clone this repo
- `bundle install` to install all requiredd dependencies
- `rake db:migrate` to make all database migrations
- `rails s` to start the local server

## Contributing

See [CONTRIBUTING](ContributingGuidelines.md).

## License
No license
