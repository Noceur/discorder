# Discorder

An interactive command line discord client, currently in it's alpha state, so bugs will be found.

If you want to join my discord channel to ask questions or do whatever then here's a link https://discord.gg/0vYlUK2XBKlmxGrX

## Dev branch

You are currently on the dev branch, things here may be breaking left and right so be carefull

##Installing/Running

#### Latest Alpha

Try the latest alpha version here: https://github.com/jonas747/discorder/releases

####compiling from repo

You need go and git installed

run this command: `go get -u github.com/jonas747/discorder`

(-u: to force an update if you have a older version)

After that there should be a built executable in your $GOPATH/bin folder

##Features

Yup, very much in development.

 - Should be light on resource usage
     + Maybe not so much in this early development stage where everything is still getting set up
 - Voice support will be added laaaaaater

Current alpha release has the following implemented:

 - Sending/receiving messages
     + You also received the changes when they get edited and removed
 - Sending/receiving direct messages EXCEPT for initiating new conversations
 - State will be saved when you leave and restored when you open again
 - Listen in on multiple channels at once!
 - History is fetched of each channel you're listening on
 - @mention autocompletion
 - Typing status, both receiving and sending 

## Usage

Run the executable and follow the instructions on screen

Controlls:

 - ctrl-o: Opens help 
 - ctrl-s: Select server/channel/private channel
 - ctrl-l: Clears the log, will later be changed to toggle hiding the log, and you can view the log in a seperate window, but thats for later...!
 - ctrl-q: Quit
 - backspace: closes the active window if any
 - arrow up/down go up/down in history and also select messages

##Screenshots


![Typing status](https://dl.dropboxusercontent.com/u/17487167/screenshots/2016-04-07T16%3A18%3A02%2B02%3A00.png)

![Mention auto complete](https://dl.dropboxusercontent.com/u/17487167/screenshots/2016-04-07T16%3A19%3A10%2B02%3A00.png)


![Logging in](https://dl.dropboxusercontent.com/u/17487167/screenshots/2016-03-16T01%3A00%3A23%2B01%3A00.png)

![Channels list](https://dl.dropboxusercontent.com/u/17487167/screenshots/2016-03-16T03%3A57%3A45%2B01%3A00.png)

![Direct messages](https://dl.dropboxusercontent.com/u/17487167/screenshots/2016-03-18T04%3A15%3A40%2B01%3A00.png)


