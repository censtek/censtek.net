---
title: "Minecraft Implements Chat Censorship Into Java Edition"
date: 2022-07-28T13:17:46-04:00
tags: ['Blogs']
draft: false
---

It looks like the dreaded change that nobody is a fan of has finally been implemented into Minecraft Java Edition. If you aren't caught up to speed, when Minecraft 1.19 was released, Mojang added a cryptographic key to each chat message sent in a server of realm to make it so that the chat message is cryptographically linked to the player that sent it. Then in a snapshot build, Mojang added a chat report feature where in any server, you could report a player's chat message under one of the categories shown below (although the profanity option was removed in a later build).

![Minecraft Chat Report Menu](/minecraftchatreportoptions.png)

Then someone at Microsoft would have access to the ENTIRE CHAT LOG OF THE SESSION (even from people that were not reported) and then look at the chat message reported + the context provided if there was any and would make a decision to ban your account from ALL OF MINECRAFT MULTIPLAYER or not.

Yeah thats right, if you get banned for a chat message that someone reported in one server, you are banned from joining any server in the entire game, even if it's just a private server for your friends. This also applies to Realms.

![Minecraft Ban Screen](/minecraftban.jpg)

This has been a really unpopular decision and has made Microsoft recieve a lot of backlash, from server owners and normal players. If you don't know, Minecraft Java Edition is a decentralized game so all of the multiplayer servers (with the exception of Minecraft Realms) are community ran and are not run by Microsoft. Mojang has trusted server owners to moderate their server the way they see fit for years and that system has worked great. But Microsoft seems to want to insert themselves into this by trying to moderate their servers for them. And if you get banned by Microsoft, you are banned from all servers, not just the one you got reported in. If you pay money to maintain a server, you should be in charge of how you want the server to be moderated. If Microsoft owned all theses servers, this change would be a lot more understandable. But Microsoft doesn't own these servers, the community does. So Microsoft shouldn't have any control over how these servers are run since they don't own them.

Luckily for players who don't want their messages to be reportable, [this mod](https://www.curseforge.com/minecraft/mc-mods/no-chat-reports) makes your messages not cryptographically signed so it is impossible for them to be reported in game. And also for server owners who don't want any chat messages in their server to be reportable, [this plugin](https://www.spigotmc.org/resources/noencryption.102902/) will also make the messages for everyone in the server to not be cryptographically signed. Although keep in mind that none of these plugins / mods will let already banned (by Microsoft) players able to join your server.

Now that Minecraft 1.19.1 was released, this chat reporting feature will effect everyone using 1.19 and up, unless you are using the mod / server plugin mentioned before. But ofc Microsoft wasn't just gonna let these server owners have freedom over their servers without trying to scare the player first. Now if you join a server with a plugin that prevents chat reporting, you'll get this warning trying to spook you

![Gay Microsoft Warning](/microsoftmoment.jpeg)

But really all this warning means is that you are actually safer in that server since nobody can report you in it.

<div id="cusdis_thread"
  data-host="https://cusdis.com"
  data-app-id="5ae39b70-fc22-4616-8a54-5b800e15a5d5"
  data-page-id="10"
  data-page-url="https://censtek.net/microsoft-implements-chat-censorship"
  data-page-title="Minecraft Implements Chat Censorship Into Java Edition"
></div>
<script async defer src="https://cusdis.com/js/cusdis.es.js"></script>