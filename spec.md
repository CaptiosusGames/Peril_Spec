
Functional Specification for Peril
==================================

Peril
-----
Peril is a territorial dominance strategy game for multiple players.

### Goals

* Experience with industry standard scalable components
* Experience making specs and APIs such that they can be re-used in multiple clients and servers
* Designing such that servers/clients/services could be turned into an income stream

User experience
---------------

### Signup / Login

New users can sign up a new account which is kept locally on the server, or authenticate with OAuth using existing services such as Google or Facebook.

## Signup

User should be able to put in a username, email, password, and potentially an avatar or Gravatar. User should recieve an email confirmation.

## Login

TBD: OAuth is desired, but not the highest priority yet. 

## Forgotten passwords

Need to figure out how to handle this for non-web clients. An email probably works, but would necessitate a web interface for handling this.


### Lobby

Presented as a chatroom where players can see each other's presence and initiate a new game.

### War Room

The war room presents game parameters and lets players invite others before the game starts.

### Gameplay

The game itself....TBD

