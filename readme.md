# TCP-Chat-Server
I am going to be making a TCP Chat Server using TCP Sockets.


# Setup

Be sure to install the Requirments.

Start the Server.py file either on some sort computer, workstation or server. and then you will be able to start the client.py

The client will ask for a username and password to login And the server will validate them.

# Command Usage
Commands are stored in the Commands.py file. Here you can edit command functionality easily and change whatever you want. There is a Temp.py file acting as a intermdiary for the Commands and Server file. This file stores some client information and general data sets. Kind of like a local mini data base. 

Command Usage is pretty simple. The defualt prefix is a double forward slash: //. The commands and arguments are as follow :
<> = Required, () = optional

help   ->  returns a useful list of available commands and their usages.
delete-channel <channel name>   ->  Deletes the specified channel name if it exists.
users  ->  returns a list of all online users in the server.
user-count     ->  returns a numeric amount of users online.
banned-users   ->  returns a list of all banned-users.
broadcast <message>    ->  broadcasts a message as the server.
ban <username> (reason)    ->  bans a user with an optional reason.
unban <username> ->    unbans a specified user.


# Recent Updates
- Added a new ping system for clients that did not close.
- New WIP GUI.
- New messaging format for server-client messages
- Added type hints and some documentation

# Todo and Future
To Add
- [] Commands
- [X] Login System with password
- [] Color Checks for usernames 
- [X] More commands and a new system to send data across networks. (SSL / TSL)
- [X] An SQL database for hashed + salted logins.
- [] GUI for clients
- [] Server clustering for load balancing and to create larger networks.
- [X] Private Channels
- [] Message control features for server side (Allows complex functions and commands that can recieve input and responses) 

To Fix
- [] Better performance with multiple users 
- [] Connections being interupted
- [] Color checks and meta data in messages
- [ ] Any erros still missing that havent been updated...
Some current bugs are as follows -
  X
  
I plan on adding tons of new stuff and cool features so any suggestions are awesome! This server is not safe for anything other than private use, i'm certain that there are vulnerabilities in this project which i may not be aware of. :)
Enjoy!
