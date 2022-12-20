# MIABOT- Discord Meet Scheduler Bot

This repository describes the working of a discord meet scheduler bot using python.

![hehe](https://user-images.githubusercontent.com/85625961/208255209-dc19cd68-9a97-45d1-85f8-94f8601b9b0d.jpg)



## Prerequisite

* Python 
* Github
* Git
* VS Code
* Discord

## Installations

* Install latest version of python [python 3.11.1](https://www.python.org/downloads/)
* pip install necessary packages like discord.py, asyncio, viertualenv(optional)
* [Git](https://git-scm.com/downloads)
* [VS Code](https://code.visualstudio.com/download)
* [Discord](https://discord.com/download)

**USAGE OF DISCORD AND DISCORD BOT**

Discord is a voice, video, and text chat app that's used by tens of millions of people ages 13+ to talk and hang out with their communities and friends.


![2022-12-17 (2)](https://user-images.githubusercontent.com/85625961/208255691-3fdb8d27-7453-408b-a502-da056d7f2918.png)

It's much easier to set up a Discord server and share the link with other users. The main goal here is to bring people together

Before creating your server, you have to get a Discord account set up. 

* Install the Discord app, then open it to continue the setup process.
* Press the Register button and enter your phone number or email address.
* Hit Next. Then you can input a Discord username and password you want to use for your account.
* Enter your date of birth, and then press the Create an account button to finish up here.
* From the main Discord app screen, tap the + button in the upper left corner.
* You use the Create My Own option to start an entirely new server or use any of the templates as needed.
* Decide if your Discord server is for a public community or you and your friends.


<h1> DISCORD BOT</h1>

Discord bots are AI-driven tools that can help you automate tasks on your Discord server. They make it a lot easier to build a community that is truly engaged and can be used to moderate your server, welcome new members, or even ban people who are creating a bad environment for everyone else.
<h3>Creating meet schedular bot</h3>

First of all we are creating a discord bot account
* Log in to the [Discord website](https://discord.com/).  
* Navigate to the [application page](https://discord.com/developers/applications)
* Click on the “New Application” button and give the application a name and click “Create”.
* Create a Bot User by navigating to the “Bot” tab and click “Add Bot”, click “Yes, do it!” to continue.
* Copy the token using the “Copy” button(Token is essentially your bot’s password, you should never share this with someone else.).


### Programming Bot
* Create a new repository in github
* Clone the repository using Git.

```
git clone https://github.com/lekshmi-02/Mia.git
```

### Bot Services

* Any members in a server can easily schedule meets using this bot!!
* Member who wants to conduct the meeting specifies the date and time of the meeting using !date and !time   commands.
* Bot takes date and time as input for scheduling.
* User can create poll by using !poll command.
* Following that bot will create a poll for the users in the poll channel of the server.
* If majority of the members agreed to the poll the the bot will send the details of the meeting in the     announcement channel of the server. 


# List of functions


List of all functions used within this project.

---

| Functions | Description |
| --------- | ----------- |
|getenv()|getenv() method is used to extract the value of the environment variable key if it exists.|
|on_ready()|on_ready() event is called when the bot has finished logging in and setting things up|
|on_message)|on_message() function listens for any message that comes into any channel that the bot is in.|
|convert_time()|convert_time() function is used to convert user input time which is in the railway time format to 12 hour format.|
|convert_date()|convert_date () function is used to format user input date|
|command()|convert_date () function is used to format user input date|
|date()[user-defined|date function is used to take input from user where date, month and year is taken separately.|
|time()[user-defined]|time function is used to take input from user where hour and minute is taken separately.|
|poll()|poll() function creates poll for the server, where users can react to the schedule.|
|sleep()|sleep function stops the entire execution of the program for a specific time. |
|send()|The send() method returns the next value yielded by the generator, or raises StopIteration if the generator exits without yielding another value.|
|fetch_message()|fetch_message function is used to fetch the count of users who reacted to the poll.|

# License

[![mit1](https://user-images.githubusercontent.com/85625961/208289339-9fc9a81e-53f3-46d4-bb1e-d34dd8cbf4e5.jpg)](https://opensource.org/licenses/MIT)


<H3> Connect with me : <H5>https://www.linkedin.com/in/vyshnavi-v-538ba9213/ </H3>

