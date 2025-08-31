 # Blockbusters
This is the official GitHub page for the Blockbusters modpack!  
This page is a source of information and a troubleshooting guide, all files/versions of the modpack itself are published on Curseforge.

### In This Guide
- [Setup](#setup)
  - [Install Curseforge & Modpack Profile](#install-curseforge--modpack-profile)
  - [Recommended settings](#recommended-settings)
- [Troubleshooting](#troubleshooting)
  - [Modpack not launching/crashing on launch](#modpack-not-launchingcrashing-on-launch)
  - [Poor Performance](#poor-performance)
- [Blockbusters GPT](#blockbusters-gpt) 
- [Links](#links)

---
## Setup

### Install Curseforge & Modpack Profile

1. Download [Curseforge](https://www.curseforge.com/download/app#download-options) (select the standalone version for your OS)
2. Once inside the Curseforge launcher, click the *+* on the top left to *Add a game*. Select *Scan computer for games* and that should automatically locate your Minecraft installation. (If it does not, type *%appdata%* in the search bar of your Start Menu and       hit enter, double click the *.Minecraft* folder and copy-paste the directory under *Manually add a game* in the Curseforge launcher.)
3. Once you've successfully added Minecraft to your games on Curseforge, install the latest version of the modpack profile for [Blockbusters](https://www.curseforge.com/minecraft/modpacks/blockbusters/install/6948697) (if the link does not work, just head to the *Minecraft* tab you added on the lefthand sidebar, and in the search bar at the top enter *BlockbustersSMP* and you should see our modpack come up.)
4. Once the modpack installs you are ready to play, no additional setup required. However, **PLEASE READ THE RECOMMENDED SETTTINGS BEFORE CONTINUING!**

### Recommended Settings

**It is highly recommended that you read this list and apply any necessary/desired settings to avoid any unwanted issues or poor performance**  

 Head to the *Curseforge* settings, under *Game Specific*, select *Minecraft*
 
- Under *Launcher Settings* select *Skip Launcher with Curseforge* (the vanilla minecraft launcher often causes issues loading this modpack, this setting will use curseforge to load the game instead)

- Under *Allocated Memory* it is recommended to select *Recommended by author*. Either way, make sure your RAM slider is set to 8000MB(8GB). Now this can be a little more complicated. You may need to adjust this based on     your system hardware, i.e., if you know you have only 12GB of system RAM, and using 8GB on minecraft isn't leaving enough for your machines basic funcions/tasks, you may need to turn it down some. That being said,     if you find yourself wanting to increase the slider, know that it is not recommended to      exceed 8GB, and anything more than 12GB is 100% overkill, and will almost certainly cause issues.

# Troubleshooting

### Modpack not launching/crashing on launch
There could be several causes for this... 
One of the most likely cause is Java, *or the lack thereof*. The easiest way to fix this would be to run the vanilla version of minecraft 1.20.1 once, which should automatically install the correct java version.
If you are still having this issue after running the vanilla version of Minecraft, you'll have to download Java 17 manually, as this is the Java version Minecraft 1.20.1 runs on. Reference [this video](https://www.youtube.com/watch?v=syW8hEPQRRg) for help.
If you do ALL of this and you are still having this issue, it may be because you have other Java versions on your pc taking priority over Java 17. If so you'll have to change this, you can do this in the curseforge launcher. Go to the game specific setttings>Minecraft>scroll down to the bottom and under Java Versions choose Java 17 and select Java 17 in your file explorer. 

### Poor Performance
Modded Minecraft is very taxing, espically this modpack. That being said don't be surprised if you're getting less fps than you'd expect from vanilla Minecraft. If you are getting exceptionally bad frame-rate or other issues like lagging, disconnecting, or poor performance in general, try these steps:
1. Check the allocated memory in your Curseforge settings for Minecraft, and adjust them if needed (reference the ⁠[Recommended Settings](#recommended-settings)).
2. You can try turning down your render distance, simulation distance, and graphics quality in the videos setting in-game. (Simulation distance means how far away from your player the game loads mobs and other process heavy tasks, setting this at the minimum will     result in a huge performance increase with likely no noticeable difference in gameplay.)
3. You can try adding these custom JVM arguments to your game client to help with performance:  
   -XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
   (this may result in a slower load time, but should greatly increase the perfomance of Java, and how much RAM it is using on your machine)

# Blockbusters GPT

If you need any additional help with torubleshooting, or if you need help with anything in-game, ask [Blockbusters GPT](https://chatgpt.com/g/g-689e8843bbf481918d25498c1a97a2a8-create-block-buster)! Blockbusters GPT was desinged by one of our own players to help us diagnose issues with our mod pack. It knows every last thing about this mod pack and can help with just about anything you need related to Blockbusters!

## Links

- [Curseforge](https://www.curseforge.com/) -Mod repository site where this modpack is hosted
- [Blockbusters](https://www.curseforge.com/minecraft/modpacks/blockbusters) -Curseforge webpage for this modpack
- [Blockbusters GPT](https://chatgpt.com/g/g-689e8843bbf481918d25498c1a97a2a8-create-block-buster) -A helpful GPT that can be used as a tool to help you solve any issues in this mod pack
