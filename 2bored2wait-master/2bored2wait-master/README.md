# How to install
1. Download and install node.js version 14 or above and git.
-Link to node.js https://nodejs.org/en/
-Link to git https://git-scm.com/downloads
2. Download This repo by clicking the green code button and click save as zip.

4. Open Command prompt with admin rights
5. Navigate to the downloaded folder
6. Copy config.json.example and name it config.json. Replace DISCORDBOT_FLAG and WEBSERVER_FLAG with true or false to your liking, then replace MINECRAFT_PROXY_PORT and WEB_UI_PORT with valid ports. Edit other values to your preference.
7. For trust reasons, this tool does not update automatically. Check back here once in a while to see if there are any updates.


```
docker run --name 2bored2wait -d -p 80:8080 -p 25565:25566 -e MOJANG_USERNAME="user@domain.com" -e MOJANG_PASSWORD="myverysecretpassword" -e BOT_TOKEN="mydiscordbottoken" -e DISCORD_BOT="true" -e WEBSERVER="true" -e MINECRAFT_PORT=25566 -e WEBUI_PORT=8080 2bored2wait
```
** Remember to change user@domain.com and myverysecretpassword with your actual Minecraft credentials, as well as mydiscordbottoken with your actual Discord Bot Token **

##TEST
