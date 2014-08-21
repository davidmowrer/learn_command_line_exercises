Alternative "english" ways of asking for your working directory:

1. Can we see what's in our production log?
    Yes.  cd into the log directory.
    enter less production.log
    git message maybe a binary file.  See any way? y enter
    This will display the content of the production log.
    Enter q (quit) to get out of the display.

2. What does our database.yml look like?
    From the directory you are in cd config
    less database.yml
    This will display the content of the database.yml.  
    It will look a kind of like the below text.
    
    # SQLite version 3.x
    #   gem install sqlite3
    #
    #   Ensure the SQLite 3 gem is defined in your Gemfile
    #   gem 'sqlite3'
    #
    default: &default
      adapter: sqlite3
      pool: 5
      timeout: 5000
    
    development:
      <<: *default
      database: db/development.sqlite3

3. Do More:
    I did all the do more task.
