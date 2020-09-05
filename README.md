# Tantra Offline (Kathana 3)

## How to run the server

1. Copy the content of this repository into the path 'C:/Server'
2. Open 'TantraTool.bat' file
3. Press 'G' and 'ENTER'
4. Start 'DBSRV' (letter 'V')
5. Start 'MSGSRV' (letter 'W')
6. Start 'CHATSRV' (letter 'X')
7. Start Zones (letters 'A-U')

F.Y.I: Download all the zones using the following link: https://drive.google.com/drive/folders/1GfLlUeS0pl_2QS2QSS-jCU3tA5zGNrz4?usp=sharing . Create a new folder called 'ZONES' inside 'C:/Server' and put all zones folders there.

## How create account

1. Open the 'TOOLS/Create Account' file.
2. Fill the form and save.
3. Copy the generated file (.TAD) to the 'DBSRV/account/${first letter of file}' path (I.E: 'DBSRV/account/T/TEST.TAD').

## How to connect to the server

1. Open offline client and start the game.

## If you dont have the client (NOT TESTED)

1. Download this patch from this url: https://drive.google.com/drive/folders/1jQ4D7IkpKe0_2TcnAG38uE401avGB7e7?usp=sharing
2. Apply the patch to a Kathana 4 client.
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