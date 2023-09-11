# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

- Create a secret key base locally by:

1. Remove config/master.key and config/credentials.yml.enc if they exist.
2. Run in the terminal: EDITOR=code rails credentials:edit 
3. Close the editor that opens.
4. This command will create a new master.key and credentials.yml.enc if they do not exist.
