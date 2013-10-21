---
        layout: page
        title: Softwarewolves

---

The Game
========

Softwarewolves is a variant of the [werewolves game](about.html) played online over chat, involving both human an bot players. In the screenshot below you can see part of the voting round in which the villagers vote who should be hanged.

![](https://raw.github.com/softwarewolves/softwarewolves.github.io/master/images/screenshot.png)

As a participating team, your goal is to build a bot player that participates in the game. A product owner will publish stories for specific functionalities and their corresponding reward, such as
* voting according to specific voting behaviors
* playing the role of the werewolf
* tracking the voting history of other players

Teams can earn marks by succesfully demoing one or several stories to the product owner. 


Technology
----------
The game is played over online chat. Players meet in a chatroom where the game takes place. The underlying technology used for the Softwarewolves game is [Extensible Messaging and Presence Protocol (XMPP)][1]. Players are XMPP clients, and connect to an XMPP server. XMPP enables connecting players written in different languages and technologies.

But don't worry, you don't need XMPP knownledge to build a bot for softwarewolves. We provide basic bot implementations that encapsulate the XMPP-protocol so that you can start with minimal technical hurdles. Basic bots are available in the following programming languates:
- C#
- Java
- Ruby
- Node.js
- Scala
- Other languages available at request
 
Infastructure
---
Our state-of-the-art game server is a raspberry pi. Did you know that requires less energy in an hour than a jumbo jet in a millisecond?

![](https://raw.github.com/softwarewolves/softwarewolves.github.io/master/images/pi.jpg)




[1]: http://en.wikipedia.org/wiki/XMPP

