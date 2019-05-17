# Slurty

A database-powered quote generator with a mobile-first design, using the Ruby on Rails framework, HTML, and CSS.

## Setup
1. Clone the repository:
``` 
	git clone https://github.com/oOCrystalOo/ruby-splurty.git
	cd ruby-splurty
```
	
2. Install bundle, create a database, and run migration
``` 
	bundle install
	rake db:create
	rake db:migrate
```
	
### Notes
This project uses postresql, and was created with ruby 2.5.3 and Rails 5.2.3. Quotes will have to be created before the landing page will start showing a random quote pulled from the database.