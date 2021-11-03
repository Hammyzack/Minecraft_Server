# Minecraft_Server

# Steps
- **Install Java** from command line
```
sudo apt install openjdk-16-jdk-headless
```
- **Download** your server jar file from [Here](https://www.minecraft.net/en-us/download/server)
- **Open a command prompt** or a terminal interface.
- Type ```cd``` (change directory), followed by the path to the folder where you placed your server jar file.
- Run the server for the first time by typing ```java -jar file_name_here.jar --nogui``` in the command line.
- Next type ```eula.txt``` on the command line
- Open it in a text editor and change ```eula=false``` to ```eula=true```
- Now the server has been set up, and you can simply run it with ```java -jar file_name_here.jar```
- After everything is done type on the command line ```java -Xmx1024M -Xms1024M -jar file_name_here.jar nogui```
