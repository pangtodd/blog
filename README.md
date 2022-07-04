# Bloggy project

#### By Todd Pangilinan

#### WORK IN PROGRESS (personal exploration)
a simple Ruby-based blog site.

## Technologies used:

* Ruby on Rails
* RSPEC
* Pry
* markdown
* Postgres
* SQL


## Description:
Using Ruby on Rails and Postgres, this Ruby-based application allows a user to create blog posts, and it allows others to comment.. Both blog posts and comments are able to be created, read, updated, and deleted, demonstrating full CRUD capabilities. 


## Setup/Installation Requirements

* If you don't have git installed on your machine, follow these [instructions.](https://www.learnhowtoprogram.com/introduction-to-programming/getting-started-with-intro-to-programming/git-and-github)
* Via your terminmal, navigate to the directory you want to store my files in.
* Clone my git hub directory by typing or cutting pasting: "git clone https://github.com/pangtodd/volunteers_projects.git" into your terminal
* To run this program, you must have Ruby 2.6.5 installed on your machine. If you do not, you can follow these instructions: [Mac](https://www.learnhowtoprogram.com/ruby-and-rails-part-time/getting-started-with-ruby/installing-ruby-on-mac) or [PC](https://www.learnhowtoprogram.com/ruby-and-rails-part-time/getting-started-with-ruby/installing-ruby-on-windows).
* Once you have the project downloaded, navigate to the root of the project in your terminal and type "bundle".
* you will also need Postgres installed on your machine. If you do not, you can follow these [instructions.](https://www.learnhowtoprogram.com/ruby-and-rails-part-time/getting-started-with-ruby/installing-postgres) 
* You will also need to create a local database and test database, using the sql backup file "database_backup.sql", which should be included in the download from github. [Instructions on creating a database from a sql backup.](https://www.learnhowtoprogram.com/ruby-and-rails-part-time/ruby-database-basics/backing-up-and-recreating-a-database)
* Make sure your database names match the named databases in the code (line 9 in app.rb and line 7 in spec helper). Keep it simple and name them "volunteer_tracker" (production) and 
"volunteer_tracker_test" (testing/development).
* After the databases are established, type "ruby app.rb" into your terminal. This should launch Sinatra.
* Please note, this application was built with a Mac system. You may need to make adjustments (such as creating adding/hiding your Postgres password) if using a PC.
* In a browswer, type in "localhost:5678". You should be able to navigate like a normal website.

## Known Bugs

As of 5/24/22:
* no known bugs (still developing).
* If you notice other mistakes or bugs, please email pang.todd@gmail.com

## License

[MIT](https://opensource.org/licenses/MIT)
Copyright 2022 (c) Todd Pangilinan 
