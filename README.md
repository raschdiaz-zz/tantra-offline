# Tantra Offline (Kathana 3/4)

## How to run the server

1. Copy the content of this repository into the path 'C:/Server'
2. Open 'TantraTool.bat' file
3. Press 'G' and 'ENTER'
4. Start 'DBSRV' (letter 'V')
5. Start 'MSGSRV' (letter 'W')
6. Start 'CHATSRV' (letter 'X')
7. Start Zones (letters 'A-U')

F.Y.I: Download all the zones using the following URL: https://1drv.ms/u/s!Agmo1jiEwGNEyC1ESi5ELDOey5sI?e=MAzByM . Create a new folder called 'ZONES' inside 'C:/Server' and put the 'ZONES' folder there.

## How create account

1. Open the 'TOOLS/Create Account' file.
2. Fill the form and save.
3. Copy the generated file (.TAD) to the 'DBSRV/account/${first letter of file}' path (I.E: 'DBSRV/account/T/TEST.TAD').

## How to connect to the server

1. Open offline client and start the game.

## If you dont have the client (NOT TESTED)

1. Download the client from this URL: https://1drv.ms/u/s!Agmo1jiEwGNEyCzY4AHPwRN8KgxZ?e=HafFbv
2. Open the 'Tantra.exe' file to edit the graphics settings.
3. Open the game using the 'HTlauncher.exe' file.

## How to modify the server IP

1. Use 'TantraTool.bat' to update the IP
2. Open 'SServer.cfg' file and update the IP

## How to modify the maps experience/gold rates:

1. Go to 'ZONES/Zone${number of zone}/Data' folder
2. Edit the file 'Settings.ini' and edit the following lines:

[Correct]
RwdPrana 	= 1000
RwdGold		= 1000
RwdBraman	= 1000
RwdItem	 	= 1000
RwdRateForNormalItem = 150

## ~~How to enable item mall:~~

~~1. Add file 'TOOLS/itemserver.txt' in Zone folder ('ZONES/Zone${number of zone}/Data'), this will require some SQL server 2002 config~~

## How to change language texts of client

1. Edit 'OFFLINE CLIENT/system/*.txl' files

## How to edit the launcher message (HTML)

1. Edit 'OFFLINE CLIENT/version.dat' file

## How to run server in public network

1. Config server with local network ip (192.168.1.#)

2. Open ports in router (1000 = login ; 3001-30## = maps)

3. Set client 'ChatServer.cfg' and 'Serverlist.txt' files  with PUBLIC IP