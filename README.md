# CrowdRescue
Disaster response and relief management for volunteer teams

## Prerequisites
You'll need Ruby and MySQL installed to be able to set CrowdRescue up locally.

## Setup
 - Clone the repository and `cd` into the repository directory.
 - Install the required gems: `bundle install`
 - Copy sample config to real config (and fill in any missing values): `cp config/settings.sample.yml config/settings.yml`
 - Same for database config: copy and fill in your real username and password: `cp config/database.sample.yml config/database.yml`
 - Set up the database: run `rails db:create`, `rails db:schema:load`,
   and `rails db:migrate`.
 - Run the server with `rails s`
