![1](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/101c752b-0959-437d-a69a-05c9a4ecebba)

# 📡Counter-Strike 2 RCON tool
This software is a **RCON** (**R**emote **CON**sole) tool that allows you to control and manage multiple local and/or remote **Counter-Strike 2** game servers at same time using the TCP/IP-based **Source RCON protocol**.

In the past, a lot of RCON tools were published, maybe the most popular was **HLSW** but currently the project is abandoned and no updates are released. Some clones like **Source Admin Tool** tried to take over but most of them are outdated and doesn't support Counter-Strike 2 at 100%.

**Source Admin Tool:** https://github.com/Drifter321/admintool

Seeing the lack of updated and functional tools to manage my own game servers i decided to code a new one by myself. I made a few intents to implement the **Source RCON protocol** and finally i build a library that is published in GitHub fut finally i decided to use another already built library made by an author called Untodesu because mine is buggy and needs a more deep testing. 

**Source RCON protocol in VB .net:** https://github.com/fpaezf/Valve-RCON-protocol-in-VB.NET
**RCON DotNET by Untodesu:** https://github.com/untodesu/rcon-dotnet

 








## The Source RCON protocol
The **Source RCON Protocol** is a network communication protocol which allows to remotely send console commands to any Source-based game server. The most common use of the RCON protocol is to allow server owners to manage their game servers without direct access to the machine where the game server is running on.

You can view more details of how the Source RCON protocol works here: https://developer.valvesoftware.com/wiki/Source_RCON_Protocol

## The Source RCON protocol






In order for commands to be accepted, the connection between client and server must first be authenticated using the server's **RCON password**, which can be set up using the console variable **rcon_password "yourpassword"** located in your **server.cfg** file.






Another **Counter-Strike 2 RCON tool** specially designed to remotely control all your CS2 servers.

This is the evolution of my other CS2 RCON tool: https://github.com/fpaezf/CS2-rcon-tool

Uses a modified and lightweigh version of RCON DotNET by Untodesu: https://github.com/untodesu/rcon-dotnet

Comments and feedback on Reddit: https://www.reddit.com/r/cs2/comments/17wzvst/another_cs2_rcon_tool/

Built with with Visual Studio &amp; .NET Framework 4.7.2.
<img alt="Windows" src="https://img.shields.io/badge/-Windows-0078D6?style=flat&logo=windows&logoColor=white"/> <img alt="NET" src="https://img.shields.io/badge/-Visual%20Basic-blue?style=flat&logo=.net&logoColor=white"/>

## Other CS2 admin tools
- Conter-Strike 2 server manager tool: https://github.com/fpaezf/CS2-server-manager
- Conter-Strike 2 server manager tool on Reddit: https://www.reddit.com/r/cs2/comments/172lgds/my_cs2_server_installerupdaterlauncher/
  
## Features
- Add/Edit/Manage your servers
- Data stored in XML files
- Handle multiple servers
- Retrieve server players list
- Kick players
- Quick server actions (add bots, change map, restart game...)
- Send console commands and retrieve responses
- Autofill console commands list
- Send/receive chat messages
- Edit/Save predefined messages
- Auto send messages
- Scheduled commands (daily at specified time or every x minutes)
- Scheduled tasks
- Application log
- Join server launching game via Steam
- Launch game with -insecure parameter
- Shutdown remote server

## Installation & use
- Add or edit the **rcon_password "your-password"** cvar inside your **server.cfg** file.
- Open the application and add a new server filling all fields.
- Start managing your servers!.
  
⚠️**WARNING:** If you're using a Docker image please, set your IP in startup commands to **+ip 0.0.0.0** or simply remove the +ip parameter. Thanks **asdfxD** for the fix.

## Screenshots
![2](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/72611fa9-77d1-4970-b30e-9e88b3923f12)
![3](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/28333a2d-81e0-4406-aa44-e638d35b7139)
![4](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/77d3f4d4-1979-4c40-aa44-aef44306c421)
![5](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/c4197c67-aa43-468b-9f7b-20575909c6cb)
![6](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/bef01e8a-bcb0-4a37-8e63-1a9df76afc14)
![7](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/72e2cb1f-960b-42a5-a8cb-9bce758300ac)
