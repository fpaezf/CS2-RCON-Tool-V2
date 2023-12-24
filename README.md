![1](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/101c752b-0959-437d-a69a-05c9a4ecebba)

# 📡Counter-Strike 2 RCON tool <img alt="Windows" src="https://img.shields.io/badge/-Windows-0078D6?style=flat&logo=windows&logoColor=white"/> <img alt="NET" src="https://img.shields.io/badge/-Visual%20Basic-blue?style=flat&logo=.net&logoColor=white"/>

This software is a **RCON** (**R**emote **CON**sole) tool that allows you to control and manage multiple local and/or remote **Counter-Strike 2** game servers at same time using the TCP/IP-based **Source RCON protocol**.

In the past, a lot of RCON tools were published, maybe the most popular was **HLSW** but currently the project is abandoned and no updates are released. Some clones like **Source Admin Tool** tried to take over but most of them are outdated and doesn't support Counter-Strike 2 at 100%.

- **Source Admin Tool:** https://github.com/Drifter321/admintool

Seeing the lack of updated and functional tools to manage my own game servers i decided to code a new one by myself. I made a few intents to implement the **Source RCON protocol** and i've coded a library that is published in GitHub but finally i decided to use a ripped and lightweigh version of another already built library made by an author called **Untodesu** because mine is buggy and needs a more deep testing. 

- **Source RCON protocol in VB .net:** https://github.com/fpaezf/Valve-RCON-protocol-in-VB.NET
- **RCON DotNET by Untodesu:** https://github.com/untodesu/rcon-dotnet

## The Source RCON protocol
The **Source RCON Protocol** is a TCP/IP-based network communication protocol which allows to remotely send console commands to any Source-based game server. The most common use of the RCON protocol is to allow server owners to manage their game servers without direct access to the machine where the game server is running on.

In order for commands to be accepted, the connection between client and server must first be authenticated using the server's **RCON password**, which can be set up using a special console variable.

You can view more details of how the Source RCON protocol works in Valve's website:
- https://developer.valvesoftware.com/wiki/Source_RCON_Protocol

## Counter-Strike 2 RCON tool Main features
- Visual servers list
- GeoIP-based servers country flags
- GeoIP-based players country flags
- Manage workshop maps
- Retrieve map group from server
- Source RCON protocol data query from servers
- Steam web API data query from servers
- Retrieve server players list via RCON commands
- Kick/Ban players by Name, Ip or ID
- Quick server actions (add bots, change map, restart game...)
- Send console commands and show the server's response
- Autofilling console commands dropdown list
- Send and receive chat messages
- Edit/Save predefined broadcast messages
- Auto send messages every X seconds
- Scheduled commands (daily at specified time or every x minutes)
- Open the game and join a server
- Launch the game with -insecure parameter
- Shutdown remote server
- Application log
  
## Installation & usage
- https://github.com/fpaezf/CS2-RCON-Tool-V2/wiki/Installation-and-Usage

## Why source code is not published?
Some people have asked me why I publish this tool on Github if it is not open source, this is my answer:

Github allows me to have a free website where I can publish updates easily, can receive users feedback and messages and in addition, people can easily find this software if they search for this kind of tools in any search engine.

Finally, coding a tool like this costs many hours of effort and research which I have invested for free. If you want to see how this program works, you can use any free and open source .NET decompiler and see it yourself, but if you want to develop a tool like this, you will have to code it yourself. At the moment I do not intend to publish the source code so, please: STOP BOTHERING ME.

## Screenshots of the tool GUI
![2](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/72611fa9-77d1-4970-b30e-9e88b3923f12)
![3](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/28333a2d-81e0-4406-aa44-e638d35b7139)
![4](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/77d3f4d4-1979-4c40-aa44-aef44306c421)
![5](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/c4197c67-aa43-468b-9f7b-20575909c6cb)
![6](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/bef01e8a-bcb0-4a37-8e63-1a9df76afc14)
![7](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/72e2cb1f-960b-42a5-a8cb-9bce758300ac)

## Other CS2 admin tools
![aaaa](https://github.com/fpaezf/CS2-RCON-Tool-V2/assets/28062918/253d78d8-0b6c-4a0e-8302-f27659c58b3d)

To easly manage my own game servers i also published a tool that allows you to install, update, start and stop the servers with just one click.

- Conter-Strike 2 server manager tool: https://github.com/fpaezf/CS2-server-manager

You can publish your comments, ask for new features or send your feedback on Reddit:
- https://www.reddit.com/r/cs2/comments/172lgds/my_cs2_server_installerupdaterlauncher/
