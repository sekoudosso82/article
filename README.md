# README

Rails API

Goals

    Initialize a Rails application in API mode
    Set up Rails to serve JSON
    Refactor existing app 

Running the App

    make sure you are in the director for the Rails app
        cd article-api
    bundle to get all the gems
        bundle install
    create the Postgres database (you should have Postgres installed)
        rails db:create
    run migrations
        rails db:migrate
    seed data
        rails db:seed
    run the Rails server
        rails s
    confirm the app is serving JSON
        http://localhost:3000/api/articles

Helpful Commands

    create a Rails app in API mode with a Postgresql database (and not as a Git repository)
        rails new article-api --api -G -d=postgresql

    create a new resource:
        rails g resource Api::article title body imageUrl

