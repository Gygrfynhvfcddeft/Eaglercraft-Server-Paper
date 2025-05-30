## Eaglercraft-Server-Paper

Universal Eaglercraft server (1.5, 1.8, 1.12) using Paper 1.12.2

Use the `run.bat` file to run on Windows, or `run.sh` to run on macOS or Linux. The server uses port **25565** for both Vanilla and Eaglercraft players.

Based on EaglercraftXServer, EaglercraftXRewind, ViaVersion, SkinsRestorer, and AuthMeReloaded.

You can also download the EaglerMOTD plugin to animate your server's MOTD, and the EaglerWeb plugin to host a website from your server, both of which are available here [https://github.com/lax1dude/eaglerxserver/releases](https://github.com/lax1dude/eaglerxserver/releases)

Fork this Repo to make it more popular

**Note:** If you would like to support versions of Eaglercraft 1.5 older than 22w34a (before singleplayer), add `-Deaglerxrewind.oldChunkFormat=true` to the JVM arguments in the run script. This will perform worse for both clients and the server, but will be compatible with every version of 1.5 going back to 2020.


## First time setting up the server(For Github Codespaces)
(You can also use this on Linux if you want, but you would need to play locally or port forward yourself)

First, you need to create a GitHub Codespaces
To make one click on the big green button that says **<>Code**
Click on the tab below the button, right next to local, that says "Codespaces"
Then click on **Create codespace on main**
Once you have loaded in the codespace then type this into the terminal:
```bash
chmod +x run.sh
```
After you've typed in that command then you are ready to start up the server
Type this into the terminal when you want to start your server up:
```bash
./run.sh
```
To connect to your new server, you need to make a port if it didn't automatically make it
Next to terminal, it should say *port* and click on it
The port should be 25565, the default port of a Minecraft Server
If there isnt any port then click on *add port* then type in **25565**
Right click on **port visibility** then click make public
Right click on it again and click on *open in browser*

## Opening the server for another time

FYI You need to do this every time you reopen the server
Type this into the terminal
```bash
./run.sh
```
open port **25565** make it visable then you are done
