# Tantra Offline (Kathana 4)

## How to run the server

1. Copy the content of this repository into the path 'C:/Server'
2. Open 'TantraTool.bat' file
3. Press 'G' and 'ENTER'
4. Start 'DBSRV' (letter 'E')
5. Start 'MSGSRV' (letter 'X')
6. Start 'CHATSRV' (letter 'Y')
7. Start Zones (letters 'A-S')

## How create account

1. Open the 'TOOLS/Create Account' file
2. Fill the form and save.
3. Copy the generated file (.TAD) to the 'DBSRV/account/${first letter of file}' path (I.E: 'DBSRV/account/T/TEST.TAD')

## How to connect to the server

1. Open offline client and start the game 

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
