---
        layout: page
        title: Softwarewolves

---

The Game
========

Werewolves
----------

Softwarewolves is inspired by the well-know party game [Werewolves](http://en.wikipedia.org/wiki/Mafia_(party_game): 
- the werewolves game models a battle between an informed minority (the werewolves) and an uninformed majority (the townspeople). Players are secretly assigned roles: either werewolves, who know each other; or townspeople, who know only the number of werewolves amongst them. 
- In the game's night phase the werewolves covertly "murder" a townsperson. During the day phase, all of the surviving players debate the identities of the werewolves and vote to eliminate a suspect. Play continues until all of the werewolves have been eliminated, or until the werewolves outnumber the townspeople. 

Softwarewolves
--------------
In softwarewolves, the game is played online over chat, involving both human an bot players. In the screenshot below you can see part of the voting round in which the villagers vote who should be hanged.

![](https://raw.github.com/softwarewolves/softwarewolves.github.io/master/images/screenshot.png)

As a participating team, your goal is to build a bot player that participates in the game. A product owner will publish stories for specific functionalities and their corresponding reward, such as
* voting according to specific voting behaviors
* playing the role of the werewolf
* tracking the voting history of other players

Teams can earn marks by succesfully demoing one or several stories to the product owner. 


Technology
----------
The game is played over online chat. Players meet in a chatroom where the game takes place. The underlying technology used for the Softwarewolves game is [Extensible Messaging and Presence Protocol (XMPP)][1]. XMPP grew out of *Jabber* and is often referred to by that name. Players are XMPP clients, and connect to an XMPP server.

Programming
-----------
But don't worry, you don't need XMPP knownledge to play softwarewolves. We provide basic bot implementations that encapsulate the XMPP-protocol so that you can start with minimal technical hurdles. Basic bots are available in the following programming languates:
- C#
- Java
- Ruby
- Node.js
- Scala
- Other languages available at request

[1]: http://en.wikipedia.org/wiki/XMPP

