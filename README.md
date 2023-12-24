# EaglerCraftX-Server
A EaglerCraftX-Server Creator
# Download Instructions
1 Access the Releases tab and Download EaglerCraftX Server.zip and EaglerXBungee.jar
2 Install WinRAR in your computer
3 Click with the right button and click extract to the Name Archive and go to the https://www.java.com https://gitforwindows.org https://ngrok.com and https://code.visualstudio.com and Download Java 8,Git For Windows,Ngrok and Visual Studio Code
4 Go to the Folder EaglerCraftX Server and Spigot 1.8.8. Entered in the folder click with the right button in the blank space and in the menu,click Open Git Bash Here
5 in the Git Bash insert this command java -jar BuildTools.jar --rev 1.8.8 and wait the code stops
6 back to the Folder EaglerCraftX Server and Enter in Folder BungeeCord
7 Entered in the Folder BungeeCord Create a new txt file and Open the Visual Studio Code
8 Press Ctrl+K and Ctrl+O and select the Folder EaglerCraftX Server
9 On the left side enter the BungeeCord Folder and rename the txt file to Start.cmd and place this command in line 1 @echo off line 3 java -jar BungeeCord.jar and in line 5 pause. After this press Ctrl+S to save the command.
10 in the Explorer launch Start.cmd in EaglerCraftX Server\BungeeCord
11 close the CMD and move the EaglerXBungee.jar for the EaglerCraftX Server\BungeeCord and plugins
12 in the Explorer launch Start.cmd in EaglerCraftX Server\BungeeCord
13 in Ngrok place this command ngrok config add-authtoken your-token replace your-token per your token in ngrok your token is obtainable in https://dashboard.ngrok.com/get-started/your-authtoken
14 In the ngrok place this command ngrok tcp --region us 8081
# Server Configuration
Use the Visual Studio Code and open spigot.yml and server.properties in Spigot 1.8.8,config.yml in BungeeCord and listeners.yml in BungeeCord\plugins\EaglercraftXBungee
Configure all the archives to online-mode to false