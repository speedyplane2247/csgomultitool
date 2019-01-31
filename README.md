# CSGO-MultiToolnoise cannoise 
CS:GO Multi-tool is a tool that is a simple AHK-based program that has enhances gameplay and makes it easier without cheating. 
## What this program does and does not do
+ This program does not never will read memeory (at least the official version, and due to the nature of the script can and likely will be adjusted)
+ This program does not aim for you, or do any sort of processing and can't detect/know where enemies are.
+ This program only changes when updates to the branch it is based off of, and will never accept potentionally dangerous code
## Help! I've been VAC Banned / Game Banned!
This product is by definition a cheat - it is an external piece of software that gives you certain advantages (albeit limited) over your enemies. Most of the features (listed below) can't really get you in trouble (unless you abuse them), but certain are very obvious (and don't really grant too much of an advantage) and can/will get you banned by Overwatch, or even Untrusted if you are unlucky. Using some of them in Casual gamemodes (10v10, Deathmatch, DZ, or War Games) may land you a VAC Authentication error - where you need to Verify your game files and restart your computer to fix. These can be bypassed by simply not abusing this program to allow you to even get anything close to something like this.

If you have recieved a VAC ban - this could be for a few reasons

In any case - Please make an issue and we'll look into it and look at any problems, but it is always nice to document bans to see any trends. For example, if a ton of VAC bans are issued on one day, we'll know that there is a problem and try to fix it. 

### A cheat software
You may have used another cheat software caused the VAC ban. We can't help this, but you can still create an issue and we will look into it, and try to fix any problems on our end.
### Older Release
If you have used a release that is very old, this is likely the reason - altough VAC shouldn't detect this, it certainly can and probably will. Creating an issue is once again useful, to document what version you used and stuff like that.
### Raw AHK Script
You can run the raw AHK script, as its available for download, or you can extract it from the EXE if you want. This poses many risks, as it isn't updated as much as the EXE version, as it doesn't have any way of changing its own signature.
### Latest EXE version
If the latest EXE version has been detected, in the pre-injection menu, select "Obtain a different signature" and you can get a different signature. Please ensure you have updated the script, downloaded the EXE and other things, and then create an issue. It is the most important to create an issue here, an we will try to fix it as soon as possible. 

## Features
Here is a list of features currently in the tool.
### Auto-fire
Auto-fire changes semi-auto peestols like the tec-9 and other pistols is available. It is enabled in the menu, but you need to disable when working with a full-auto or even burst-mode weapons, as this can cause weird bugs / slower rate of fire.
This kind of works with the AWP/Scout, but does not work with the Revolver.
### Burst-fire
This enables burst-fire on all guns. Once again this must be enabled/disabled in the menu for what you want to do it with, and works with all weapons besides the Scout, AWP, and Revolver.
### Single-fire
This can be useful with the CZ75 and M4a1-S/AK as it lets you fire only one bullet per click, instead of the current full-auto when being held down. This can be very useful when dealing with low-ammo, or just want to practice one taps.
### Auto-reload
This is all-around useful, but can mess you up sometimes. If you haven't fired for 10 seconds, and have used more than 50% of your ammo, it will automaticaly reload. This also auto-reloads when you have no ammo, no matter the circumstance. This is ruled out by single-fire mode, if you want to one-tap.
### Auto-jump
This is not a bunny-hop script, but it does auto-jump. You shouldn't bind this to space, as it doesn't allow you to move while jumping. This can be used for information peaks. Note: In the current build it does not slow you down (it can't tell the way you are moving, as it doesn't access the game), so if you have a good enough mouse-stafe, you can still move, but keyboard strafes are blocked. This feature could be removed if it is abused / causes a lot of Overwatch bans, but I will keep it in a seperate branch.
### Manual LifeSaver
Manual lifesaver is a tool that allows you to bind a key that toggles between cvar "m_yaw 0.022" (default) and "m_yaw 20". This allows your mouse to move hundreds of times faster, and doing this while planting the bomb under heavy enemy fire can confuse enemies and even some aimbots/triggerbots. This will not get you an overwatch ban, (maybe unless you somehow get a kill using it, but the odds of that are insane) This still requires fast manual mouse movement from you, but is much better than frantically hitting your DPI buttons, and good luck getting back to your regular DPI and then killing the 4 enemies staring you down with guns firing. (Unless its a toggle-switch, then do that!)
### Auto LifeSaver
Auto lifesaver is a grey area in terms of CS:GO scripts. Some, such as autofire/sensitivity binds are completely allowed, but this requires no input from you, and creates a pattern that can be very easily modified for cheating. It cycles in a constant insanely fast 360 degree turn, with a slower pitch up and downwards, covering virtually angle possible within about 250 units, and a headsize angle from up to 2200 units. Combined with a triggerbot / aimbot (which we do **not** agree with) this could be a very deadly form of Anti-aim, and mimics a spinbot. This isn't its intended purpose, it is supposed to allow to survive in the crucial final seconds of a round as a CT trying to avoid death, or a terrorist planting the bomb while being shot at from many different angles. Please do not abuse this, but this is open-source for a reason, and you can mod it however you'd like. This can get you an overwatch ban, as it normal speed it is too fast to see what is happening, but in slow-motion (host_timescale 0.1 for reference) it is clearly too smoooth for a human to do consistantly, and will likely land you a ban. 

## Safety
This is open-source, and AHKs are easily detectable by VAC, especially if modded to hook into the game. Do not use this on any prime accounts, as I can't guarentee safety, and also please don't use this in an abusive way that could lead to OW bans. Also, I doubt it will be detected for a while, but do not use this on ESEA/FACEIT/other services as it will soon be detected there. 

Thank you for reading, speedyplane2247.
