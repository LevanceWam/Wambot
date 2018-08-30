# Wambot
Hello and welcome to the Wambot!
This is a discord bot that is an extension of the Full Sail Armanda's Max Bot.
This is a class project that I have been keeping up with out side of the class.
The project holds a special spot for me because at the time of developing I knew nothing about node.js.
This lead to countless hours of me researching, practicing, and testing to keep up with my teammates and pass the class.

Please follow the link: https://github.com/reactivepixel/Max-Bot

To see official documentation for the max bot and how it works.

## Functionality 
The Wambot main job is to send out a email that invites Full Sail students and grants them access to the Full Sail Armanda. If you do not have a Full Sail email I am sorry but you cannot join the server.

The other job is to add text and voice channels to the user discord list of channels.

The Wambot responses to user input so using the right commands will help you

## Tools needed

These are some of the tools you will need if you want to run Wambot locally:

```
Node
Vacant email address
Docker
Eslint
Gulp
Wireless Hotspot
MySQL
```
The vacant email is needed so that Wambot can send the email link to the other users. You need to go to your email provider’s settings and grant it access 

The wireless Hotspot is needed to allow Wambot to send the email the mailer package that is included with the wambot hits a security issue with Internet providers so to avoid this we use the hotspot to send the emails.

All other functionalities will work on provided Internet services.

## ENV Vars

Create an ```.env``` file with the following sensitive information. Replace the "xxx"'s with some unique information for your local Environment.

```
NODE_ENV=development
DEBUG_MODE=3

MYSQL_ROOT_PASSWORD=xxx
MYSQL_USER=xxx
MYSQL_PASS=xxx
MYSQL_DATABASE=max
MYSQL_HOST=mysql
DB_PORT_HOST=3306
DB_PORT_GUEST=3306

DISCORD_BOT_TOKEN=xxx_bot_token_from_next_step_xxx

BOT_PORT_HOST=80
BOT_PORT_GUEST=3000

EMAIL_USERNAME=xxx
EMAIL_PASS=xxx
```

## Install & Run

You will need to download Docker and MySQL if you do not have it on your machine.

```
npm -i
```
This will install all the packages need to get Wambot up and running.

Run this command to set up Docker and set up the environment to have Wambot active.

```
docker-compose up
```
Once you build is successful you can enjoy the Wambot.

# Final Statement 

There are still one more step to fully get the Wambot up and running which will be allowing access to the discord though the discord developer page.
Please refer to the official Full Sail Armanda Max Bot for help on this issue: https://github.com/reactivepixel/Max-Bot

Thank you and enjoy using the Wambot.