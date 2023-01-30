# Welcome to My Users App
***

## Task
Create a RESTfull web application by using Ruby framework - Sinatra. We need to create User Model, User Controller and some views.

## Description
I structured my project into few parts, such as:

    1. app
        1. controllers - Here I placed UserController, which responsible for routing
        2. models - User Model which manipulate data from our database
        3. views - Here we have 2 templates : login and index
    2. config
        1. database.yml (database yaml configuration)
        2. environment.rb (environment settings)
    3. database(db)
        1. migrate folder (for our database migrations)
        2. development.sqlite (our database)
        3. schema.rb (auto-created file)
    4. spec
    5. config.ru (ruby project configuration)
    6. Gemfile (our extension packet manager)
    7. Rakefile
Also, We need to save our session which contains user_id field.

## Installation
You just need to clone my repo from github, and store it on your local machine. First of al, run 
    <span>>bundle install </span>
    To install all packets (bundles)
    <span>>shotgun -p PORT</span>

## Usage
To start my project you need to lunch via
    >shotgun -p PORT
If you want to send cURL, send it to 
    >cURL POST 127.0.0.1:PORT -d "firstname=value1"

### The Core Team
Nurmukhamed Nurkamal

<span><i>Made at <a href='https://qwasar.io'>Qwasar Silicon Valley</a></i></span>
<span><img alt='Qwasar Silicon Valley Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
