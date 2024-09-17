# WindowsGSM.NuclearDawn
🧩WindowsGSM plugin that provides NuclearDawn Dedicated server

## PLEASE ⭐STAR⭐ THE REPO IF YOU LIKE IT! THANKS!

### Notes
- If local connections work but not External: see chapter Portforwarding
- if Serverlisting does not work, see GSLT chapter below
- Check serverfiles(click Browse=> serverfiles)/nucleardawn/cfg/server.cfg for game settings

### WindowsGSM Installation: 
1. Download  WindowsGSM https://windowsgsm.com/ 
2. Create a Folder at a Location you wan't all Server to be Installed and Run.
3. Drag WindowsGSM.Exe into previously created folder and execute it.

### Plugin Installation:
1. Download [latest](https://https://github.com/Raziel7893/WindowsGSM.NuclearDawn/releases/latest) release
2. Either Extract then Move the folder **NuclearDawn.cs** to **WindowsGSM/plugins** 
    1. Press on the Puzzle Icon in the left bottom side and press **[RELOAD PLUGINS]** or restart WindowsGSM
3. Or Press on the Puzzle Icon in the left bottom side and press **[IMPORT PLUGIN]** and choose the downloaded .zip

### Official Documentation
🗃️ Didn't find any documentation yet. Please Let me know if you came accros one

### The Game
🕹️ https://store.steampowered.com/app/17710/Nuclear_Dawn/

### Dedicated server info
🖥️ https://steamdb.info/app/111710/info/

### Port Forwarding (YOU NEED THIS, TO BE ABLE TO CONNECT FROM THE INTERNET(only for servers/pcs at home):
- If You don't know How: portforward.com
- 27015 TCP&UDP - Default Query And Game Port
- 27020 UDP 	- Default Steam Port
- 27005 UDP		- Default clientport

### Available Params
All these params are automatically set by WGSM, you can change them by clicking Edit Config (DO NOT ADD THEM IN SERVER START PARAM)
- -console -game nucleardawn 	default params
- -ip  	 	                 	can be change and working (Change via WGSM settings)  if you have issues try 0.0.0.0
- -port  	 	                can be change and working (Change via WGSM settings)
- -map  	 	                can be change and working (Change via WGSM settings)
- +sv_setsteamaccount			Set your GSLT token in Edit Config Window

# Registering Game Server Login Token (GSLT)
#### To navigate this on WGSM click Edit config button and you will see Server GSLT field

1. Generate a token for your game server [View](http://steamcommunity.com/dev/managegameservers) 
2. App ID of the base game (111710)
3. Memo (text stored with the account, just shown here to help you keep track)
4. Paste the Login Token on your WGSM GSLT text field.

### How can you play with your friends without port forwarding?
- Use [zerotier](https://www.zerotier.com/) folow the basic guide and create network
- Download the client app and join to your network
- Create static IP address for your host machine
- Edit WGSM IP Address to your recently created static IP address
- Give your network ID to your friends
- After they've joined to your network
- They can connect using the IP you've created eg: 10.123.17.1:7777
- Enjoy

### Support
[WGSM](https://discord.com/channels/590590698907107340/645730252672335893)

### Give Love!
[Buy me a coffee](https://ko-fi.com/raziel7893)

[Paypal](https://paypal.me/raziel7893)

### License
This project is licensed under the MIT License - see the <a href="https://github.com/raziel7893/WindowsGSM.NuclearDawn/blob/main/LICENSE">LICENSE.md</a> file for details

### Thanks
Thanks to ohmcodes for the Enshrouded and Palworld Plugins which i used for guidance to create this one
