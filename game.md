---
        layout: page
        title: Softwarewolves

---

The Game
========

Werewolves (also known as [Mafia](http://en.wikipedia.org/wiki/Mafia_(party_game)) is a party game with roots in social psychology: 
- the werewolves game is a battle between an informed minority (the werewolves) and an uninformed majority (the townspeople). Players are secretly assigned roles: either werewolves, who know each other; or townspeople, who know only the number of werewolves amongst them. 
- In the game's night phase the werewolves covertly "murder" a townsperson. During the day phase, all of the surviving players debate the identities of the werewolves and vote to hang a suspect. Play continues until all of the werewolves have been eliminated, or until the werewolves outnumber the townspeople. 

Softwarewolves is a variant of this party game played in a chatroom, involving both human an bot players. 

The organizers provide the infrastructure, a game engine and some basic bots to start from. As a participating team, your goal is to build a bot player that participates in the game. A product owner will publish stories for specific functionalities and their corresponding reward, such as
* voting according to specific voting behaviors
* playing the role of the werewolf
* tracking the voting history of other players 

Teams can earn marks by succesfully demoing one or several stories to the product owner. 


Technology
----------

The underlying technology used for the Softwarewolves game is [Extensible Messaging and Presence Protocol (XMPP)](http://en.wikipedia.org/wiki/XMPP). Players are XMPP clients, and connect to an XMPP server. XMPP enables connecting players written in different languages and technologies.

But don't worry, you don't need XMPP knownledge to build a bot for softwarewolves. We provide basic bot implementations that encapsulate the XMPP-protocol so that you can start with minimal technical hurdles. Basic bots are available in the following programming languages:
- C#
- Java
- Ruby
- Node.js
- Scala
- Other languages available at request
 
Infastructure
---
Our state-of-the-art game server is a raspberry pi that runs ejabberd. Did you know that requires less energy in an hour than a jumbo jet in a millisecond?

![](https://raw.github.com/softwarewolves/softwarewolves.github.io/master/images/pi.jpg)


