# Echo project
### Discord-like app made open-source using Electron and React!
Our goal is to bring the simplicity of Discord, and merge it with the self-hosted nature of TeamSpeak, while keeping everything open-source.

## Main features
+ High quality voice calls
+ High quality screen shares
+ Room chat
+ Private calls (Planned)
+ Multi-guild support
+ Intutitive UI
+ And, of course, open-source!

## Server architecture
The vision for the app is to be able to have multiple official hosts to which people can create their own servers, plus allow users to host their own servers on their own hardware if they prefere doing so.

## Repositories overview
+ echo-client: Everything client-side, basically Electron and the actual app
+ echo-server: Handles all the intra-client communications, also acts as a Mediasoup server
+ echo-api: Handles all client and server specific data, hosted on echo.kuricki.com/api
+ echo-website: Landing page for the project, hosted on echo.kuricki.com
+ echo-status-page: Code to handle a uptime status page (WIP)

## How to contribute
Feel free to make pull requests, we are just two guys working on a gigantic project, any help is appreciated!

## Issues, feature requests, bugs
Don't hesitate to use Github issues for anything you need!
