# Recipe App

![Preview](images/screenshot.png?raw=true)

This is a simple recipe app. You can search for almost anything and the recipe will be right in front of you.
As I am using the free API tier, I have a limit of sending 5 API requests per minute so if you find that the site is not loading, it will definitely load after a minute.

You can check out the link for this project: https://recipesbyishraq.netlify.app/

Tutorial Video: https://youtu.be/Tdw4C_5otPw

## How to run the application

### Create a .env file inside the ./server/ directory

1. Create a .env file just like .env-sample file
2. Take your Application ID and Application Key from Edamam (https://www.edamam.com/) website (sign up for the Recipe Search API and then you will get the necessary id and key for the .env) and fill out the variables APP_ID and APP_KEY.

### How to start the server

Once this repo is cloned, open a terminal and run the command:

#### "cd server"

Then run:

#### "npm install"

Finally, run:

#### "npm run start"

### How to start the client

Open another terminal and run the command:

#### "cd client"

Then run:

#### "npm install"

Finally, run:

#### "npm run start"

